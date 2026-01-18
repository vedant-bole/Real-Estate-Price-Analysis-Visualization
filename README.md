# Real-Estate-Price-Analysis-Visualization
This project scrapes real estate property listings from a dynamically rendered website using Selenium. The collected data is cleaned and structured using Pandas, including price, location, area, and BHK details. The final dataset is saved as a CSV for further analysis or modeling.
# Real Estate Data Collection using Web Scraping

## Overview

This project focuses on collecting real estate property listings from a dynamically rendered website using Python. Since the website loads content via JavaScript, Selenium is used to automate a browser and extract structured data reliably.

The scraped data is cleaned and transformed using Pandas, resulting in a dataset that includes property price, location, area (in square feet), and BHK configuration. The final output is saved as a CSV file for further analysis or machine learning tasks.

## Features

* Dynamic web scraping using Selenium
* Extraction of key property attributes (Price, Location, Area, BHK)
* Data cleaning and preprocessing
* Feature engineering (Price per square foot)
* Exportable CSV dataset

## Tech Stack

* Python
* Selenium
* BeautifulSoup
* Pandas
* NumPy

## Project Structure

* `scraper.py` – Selenium-based web scraper
* `real_estate_analysis.csv` – Cleaned dataset output
* `README.md` – Project documentation

## How to Run

1. Install required libraries:

   * selenium
   * pandas
   * numpy
2. Ensure ChromeDriver is installed and compatible with your browser.
3. Run the Python script to scrape and generate the dataset.

## Output

A CSV file containing cleaned real estate listings ready for analysis.

## Note

Websites may update their structure or restrict scraping. Selectors may need adjustment if data is not captured.

## Author

Vedant Bole
