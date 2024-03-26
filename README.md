# Web Scraping Project: Cúspide Top 100 Best-Selling Books

This project involves developing a Python web scraping script to extract and analyze data from the top 100 best-selling books on the Cúspide website, including book title, URL, price in pesos, USD, and the blue dollar conversion rate. Additionally, it will establish a MySQL database that will be updated with the data obtained through Python scraping.

## Overview

The project consists of the following main components:

- `main.py`: The main Python script for web scraping and data extraction.
- `claves.txt`: Text file containing database connection credentials.
- `README.md`: This file, providing an overview of the project.

## Dependencies

The script requires the following Python libraries:

- `pymysql`: For database connection and operations.
- `requests`: For making HTTP requests to the website.
- `BeautifulSoup`: For parsing HTML content.
- `time`: For adding delays between requests.

## Usage

1. Clone the repository to your local machine.
2. Ensure you have Python installed along with the required libraries mentioned above.
3. Update the `claves.txt` file with your database connection credentials.
4. Run the `main.py` script to start scraping data from Cúspide's website.

## Database Setup

Before running the script, make sure to set up your MySQL database and create the necessary tables using the provided SQL commands in the script.

## Disclaimer

This script is for educational purposes only. Use it responsibly and ensure compliance with the website's terms of service.

## Author

Sofía Jacky-Rosell

Feel free to reach out for any questions or feedback!
