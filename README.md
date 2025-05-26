# 📈 Nvidia Stock & News Sentiment Analysis

This project performs sentiment analysis on news headlines about Nvidia using the VADER sentiment analyzer, and correlates the sentiment scores with Nvidia's historical stock prices. It provides a visual representation to explore the relationship between public sentiment and stock performance.

### 🔍 Overview

The notebook:

- Fetches Nvidia’s historical stock data using yfinance

- Retrieves recent news headlines related to Nvidia using NewsAPI

- Preprocesses the news headlines and calculates sentiment scores using VADER (Valence Aware Dictionary and sEntiment Reasoner)

- Aggregates sentiment scores by date

- Merges sentiment data with stock prices

- Visualizes the sentiment scores alongside stock closing prices