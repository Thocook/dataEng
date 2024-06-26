# Top 10 Largest Banks by Market Capitalization ETL Project

This project extracts, transforms, and loads data on the top 10 largest banks by market capitalization from Wikipedia. The data is transformed into multiple currencies and stored in both CSV and SQLite database formats, with functionality to execute SQL queries for further analysis.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Usage](#usage)

## Introduction
This project is designed to demonstrate the process of extracting, transforming, and loading (ETL) data for a real-world application. The focus is on the top 10 largest banks by market capitalization, with data sourced from Wikipedia and converted into various currencies using exchange rates.

## Features
- Extracts data from a Wikipedia page
- Transforms data by converting market capitalization into GBP, EUR, and INR
- Loads data into a CSV file
- Loads data into an SQLite database
- Executes SQL queries for data analysis

## Technologies Used
- Python
- Requests
- BeautifulSoup
- Pandas
- NumPy
- SQLite3

## Usage
1. **Run the main script:**
    ```bash
    python banks_project.py
    ```

2. **Check the generated CSV file:**
    The file `Largest_banks_data.csv` will be created in the current directory.

3. **Check the SQLite database:**
    The file `Banks.db` will be created in the current directory.

4. **Run Queries:**
    The script includes SQL queries to:
    - Print the contents of the entire table
    - Print the average market capitalization of all banks in Billion USD
    - Print the names of the top 5 banks


