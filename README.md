# Financial News Sentiment Analyzer

## Overview
This project is a Python-based tool that scrapes financial news for specified stock tickers, performs sentiment analysis on the news using machine learning, and stores the results in a MySQL database. It's designed to help identify potentially impactful financial news in real-time.

## Features
- Web scraping of financial news from Finviz
- Sentiment analysis using the FinBERT model
- Real-time processing of news data
- Storage of high-sentiment news in a MySQL database

## Technologies Used
- Python 3.x
- BeautifulSoup4 for web scraping
- Hugging Face Transformers for sentiment analysis
- MySQL for data storage

## Setup and Installation
1. Clone this repository
2. Install required packages: `pip install -r requirements.txt`
3. Set up a MySQL database and update the connection details in the script
4. Set up a table in mySQL
5. Set the `MYSQL_PASSWORD` environment variable with your database password

## Usage
Run the script with: `python financial_sentiment_analyzer.py`

The script will continuously monitor financial news for the specified tickers and store high-sentiment news items in the database.

## Future Improvements
- Add more comprehensive error handling
- Implement logging for better tracking and debugging
- Expand the list of monitored stock tickers
- Develop a user interface for easier interaction with the stored data
- Add data visualisation, perhaps in seaborn



## Contact
Nikith Nagaraj - nikithnagaraj@gmail.com

