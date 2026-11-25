# ECC Alexandria – Laptop Web Scraper

## Project Overview
A Python web scraping project built with Selenium to collect laptop product information from ECC Alexandria, an Egyptian electronics e-commerce website.

## Website
https://ecc-alex.com/en/laptop.html

## Technologies Used
- Python
- Selenium
- XPath
- CSV

## Data Extracted
- Product Name / Description
- Current Price
- Original Price (Before Discount)
- Stock Availability
- Product Image URL
- Product URL

## Features
- Scrapes laptop products across multiple pages.
- Uses XPath to locate product containers and extract product details.
- Handles products with missing descriptions.
- Identifies products with and without discounts.
- Checks product stock availability.
- Handles missing image URLs and product links.
- Exports all collected product data to a CSV file.

## Output
The extracted product data is saved in `all products.csv`.

---

**Note:** This project demonstrates practical web scraping using Python and Selenium on a real e-commerce website.
