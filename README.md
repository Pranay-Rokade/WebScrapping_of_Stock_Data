# WebScrapping of Stock Data

This repository contains Python scripts for web scraping revenue data for Tesla (TSLA) and GameStop (GME) using `yfinance`, `BeautifulSoup`, and data visualization with Plotly.

## Table of Contents

- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
  
## Overview

This project aims to extract and visualize revenue data for Tesla and GameStop. The data is fetched using the `yfinance` library and additional web scraping techniques to gather relevant information from financial websites. The final output includes visual representations of revenue trends.
You can view the revenue data for each company here:
- [Tesla Revenue Data](https://www.macrotrends.net/stocks/charts/TSLA/tesla/revenue)
- [GameStop Revenue Data](https://www.macrotrends.net/stocks/charts/GME/gamestop/revenue)


## Technologies Used

- **Python**: A powerful, high-level programming language that is widely used for data analysis, web scraping, and machine learning. It is known for its readability and extensive libraries.

- **yfinance**: A Python library that allows users to easily access financial data from Yahoo Finance. It provides functionality for downloading historical market data, stock price information, and financial statements, making it a valuable tool for financial analysis.

- **pandas**: A popular data manipulation and analysis library in Python. It provides data structures like DataFrames and Series, allowing for easy handling of structured data. It’s essential for data cleaning, transformation, and analysis.

- **requests**: A simple and elegant HTTP library for Python. It allows you to send HTTP requests easily and retrieve data from web servers. In this project, it is used to fetch HTML content from web pages.

- **BeautifulSoup**: A library for parsing HTML and XML documents. It creates parse trees from page source code, enabling easy data extraction. It is particularly useful for web scraping, allowing us to navigate and search through the HTML tree structure.

- **Plotly**: A graphing library that enables the creation of interactive visualizations in Python. It provides a variety of chart types, allowing for the effective presentation of data insights. In this project, it is used to visualize revenue trends.


## Installation

To get started, clone this repository and install the required packages. You can do this using pip:

```bash
git clone https://github.com/Pranay-Rokade/WebScrapping_of_Stock_Data
cd repo-name
pip install yfinance pandas requests beautifulsoup4 plotly
