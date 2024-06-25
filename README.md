
README
Top 10 Largest Banks by Market Capitalization ETL Project
This project extracts, transforms, and loads data on the top 10 largest banks by market capitalization from Wikipedia. The data is transformed into multiple currencies and stored in both CSV and SQLite database formats, with functionality to execute SQL queries for further analysis.

Table of Contents
Introduction
Features
Technologies Used
Setup
Usage
Project Structure
Queries
Contributing
License
Introduction
This project is designed to demonstrate the process of extracting, transforming, and loading (ETL) data for a real-world application. The focus is on the top 10 largest banks by market capitalization, with data sourced from Wikipedia and converted into various currencies using exchange rates.

Features
Extracts data from a Wikipedia page
Transforms data by converting market capitalization into GBP, EUR, and INR
Loads data into a CSV file
Loads data into an SQLite database
Executes SQL queries for data analysis
Technologies Used
Python
Requests
BeautifulSoup
Pandas
NumPy
SQLite3
Setup
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/top-10-largest-banks-etl.git
cd top-10-largest-banks-etl
Install the required packages:

bash
Copy code
pip install requests pandas beautifulsoup4 lxml numpy
Create the exchange_rate.csv file:

csv
Copy code
Currency,Rate
EUR,0.93
GBP,0.8
INR,82.95
Usage
Run the main script:

bash
Copy code
python banks_project.py
Check the generated CSV file:
The file Largest_banks_data.csv will be created in the current directory.

Check the SQLite database:
The file Banks.db will be created in the current directory.

Run Queries:
The script includes SQL queries to:

Print the contents of the entire table
Print the average market capitalization of all banks in Billion USD
Print the names of the top 5 banks

Project Structure

top-10-largest-banks-etl/
│
├── banks_project.py       # Main script
├── exchange_rate.csv      # Exchange rates CSV file
├── code_log.txt           # Log file
├── Largest_banks_data.csv # Generated CSV file
└── Banks.db               # SQLite database file
