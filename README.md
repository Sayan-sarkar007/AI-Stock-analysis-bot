# AI-Stock-analysis-bot

This project leverages the Yahoo Finance API (via yfinance) to retrieve stock data. The data is then analyzed using Gemini AI using Langchain to provide investment suggestions for investors.

# Features
Data Retrieval: Fetches stock market data using the Yahoo Finance API.

AI Analysis: Utilizes Gemini AI for in-depth analysis of stock performance.

Investment Suggestions: Provides actionable insights and recommendations for investors based on the analysis.

# Installation

### To get started, ensure you have the required libraries installed:

### bash

pip install yfinance
Usage
Use the script to analyze stocks and receive suggestions.

### Python 
import yfinance as yf

### Example: Fetch stock data for Apple
data = yf.download("AAPL")
