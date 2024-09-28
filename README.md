# CryptoNews-AI

**CryptoNews-AI** is an AI-powered application designed to help you make informed cryptocurrency investment decisions by analyzing the latest news. It collects news articles from various reputable sources and uses advanced AI algorithms to determine if it's a good day to buy a specific cryptocurrency.

## Features

- **Real-Time News Aggregation**: Fetches the latest news about your selected cryptocurrency from multiple sources.
- **AI-Driven Analysis**: Utilizes OpenAI's GPT-3.5-turbo model to analyze news articles and summarize key points.
- **Investment Recommendations**: Provides a clear verdict on whether it's a good day to buy, based on current news and market sentiment.
- **Price Predictions**: Offers an estimated price for the near future price, helping you anticipate market movements.
- **User-Friendly Interface**: Easy to navigate, making it accessible even for users with minimal technical background.
- **Supports Multiple Cryptocurrencies**: Analyze almost any cryptocurrency you're interested in.

## Motivation

The cryptocurrency market is highly volatile and influenced by rapidly changing news and events. Manually tracking and analyzing all relevant news can be time-consuming and overwhelming. **CryptoNews-AI** was created to automate this process, saving you time and providing quick, actionable insights to support your investment decisions.

## How It Works

1. **Select a Cryptocurrency**: Choose from a list of cryptocurrencies you're interested in.
2. **News Collection**: The app gathers the latest news articles related to the selected cryptocurrency from various sources.
3. **AI Analysis**: The collected news is analyzed using OpenAI's GPT-3.5-turbo model to summarize key points and assess market sentiment.
4. **Insights & Recommendations**: The app presents:
   - A brief overview of important news.
   - A verdict indicating if it's a good day to buy.
   - An estimated price prediction for the next day.
   - Current and previous day's prices for context.

## Technologies Used

- **Python**: The core programming language for the application.
- **OpenAI's GPT-3.5-turbo**: Powers the AI analysis of news articles.
- **APIs**:
  - **CryptoPanic API**: For aggregating the latest cryptocurrency news.
  - **CoinGecko API**: To retrieve current and historical price data.
- **Flask**: A micro web framework used for building the web application.
- **Replit**: Platform used for hosting the web application.

## Installation

To run CryptoNews-AI locally, follow these steps:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/yourusername/CryptoNews-AI.git
