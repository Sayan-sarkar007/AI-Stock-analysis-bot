# AI-Stock-analysis-bot

This project leverages the Yahoo Finance API (via yfinance) to retrieve stock data. The data is then analyzed using Gemini AI using Langchain to provide investment suggestions for investors.

## Features

- Data Acquisition: Fetches real-time stock data and historical trends from Yahoo Finance.

- AI-Driven Insights: Employs Gemini AI to analyze stock performance and provide predictive insights.

- Langchain Integration: Streamlines data processing and interaction among components for efficiency.

- Overview Generation: Offers insights into stocks, aiding users in forming their own ideas while making it clear that it’s not intended for direct investment decisions.

## Technologies Used 

- Programming Languages: Python

- Libraries: yfinance, Langchain, Gemini AI


## Installation

### To get started, ensure you have the required libraries installed:

### bash

- pip install yfinance

#### Usage

Use the script to analyze stocks and receive suggestions.

### Python 

- import yfinance as yf

### Example: Fetch stock data for Apple
- data = yf.download("AAPL")
