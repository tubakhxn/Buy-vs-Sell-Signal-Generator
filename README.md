# Buy vs Sell Signal Generator

## Project Overview
This project generates buy and sell signals for stocks based on moving average crossovers. It fetches historical stock price data using yfinance, calculates short-term and long-term moving averages, and plots the results with buy/sell points.

## How It Works
- Fetches historical stock data from Yahoo Finance
- Calculates 20-day (short-term) and 50-day (long-term) moving averages
- Generates BUY signals when the short MA crosses above the long MA
- Generates SELL signals when the short MA crosses below the long MA
- Plots stock price, moving averages, and marks buy/sell points

## Installation
1. Make sure you have Python installed
2. Install required packages:
   ```
   pip install -r requirements.txt
   ```

## Example Output
The output is a plot showing:
- Stock price
- 20-day and 50-day moving averages
- Buy points (green markers)
- Sell points (red markers)

You can easily see where the signals are generated based on the moving average crossovers.
