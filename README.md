# Web-Scraping
Price monitoring of a product using Web Scraping in Python

# Fossil Watch Price Tracker

## Table of Contents
- [Introduction](#introduction)
- [Project Description](#project-description)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [How It Works](#how-it-works)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction
This Python project demonstrates how to scrape product information from a website and track the price changes of a specific product. In this case, we are tracking the price of a Fossil watch on the Fossil website.

## Project Description
- We use Python and the BeautifulSoup library for web scraping.
- The scraped data (product title and price) is stored in a CSV file for tracking changes.
- The script checks for price changes and sends an email notification when the price drops below a certain threshold.

## Prerequisites
Before running the project, ensure you have the following dependencies installed:
- Python 3.x
- BeautifulSoup (bs4)
- Requests
- Pandas

## Getting Started
1. Clone this repository to your local machine.
2. Install the required Python packages by running `pip install -r requirements.txt`.

## How It Works
- The script scrapes the product title and price from the Fossil website using web scraping techniques.
- It stores this information in a CSV file for tracking.
- The `check_price` function is called to check for price changes.
- If the price drops below a certain threshold, an email notification is sent.

## Usage
1. Update the `URL` variable in the `price_tracker.py` script to your desired product's URL.
2. Run the script.

## Contributing
If you want to contribute to this project or suggest improvements, please create an issue or a pull request.



