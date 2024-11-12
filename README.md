# Quantitative-Projects
Five quantitative Projects in Python implementing quantitative analysis. Below is an explanation of the projects:

## 1. Moving Average Crossover Algorithmic Trading Strategy
This project implements a basic algorithmic trading strategy based on the moving average crossover technique, allowing users to backtest and evaluate its effectiveness on historical stock price data. The strategy is designed to generate buy and sell signals using two moving averages (short-term and long-term) to identify potential entry and exit points.
- Buy Signal: Triggered when the short-term moving average crosses above the long-term moving average, indicating a potential upward trend.
- Sell Signal: Triggered when the short-term moving average crosses below the long-term moving average, indicating a possible downward trend.

<b> Features </b>
- Data Loading and Processing: Imports historical stock data for analysis and modelling.
- Moving Average Calculation: Calculates short-term and long-term moving averages to identify crossovers.
- Signal Generation: Detects crossover events to produce buy/sell signals.
- Backtesting Framework: Simulates the strategy on historical data to evaluate performance.
- Performance Metrics: Compares strategy returns against a simple buy-and-hold approach with cumulative returns.

<b> Usage and Customisation: </b>
Users can adjust the parameters for short-term and long-term moving averages to explore how different settings impact performance. Additionally, this project provides a foundation for incorporating advanced features, such as stop-loss mechanisms, momentum indicators, and volatility filters.

## 2. Stock Price Movement Prediction using Supervised Machine Learning
This project aims to predict stock price movements using historical data. It involves collecting stock data, cleaning and preprocessing it, and then building and evaluating various machine learning models, such as K-Nearest Neighbors, Logistic Regression, and Decision Trees. The goal is to identify the best-performing model for predicting whether a stock's price will increase or decrease over a specific time period. 

<b> Features </b>

- Data cleaning
- Feature engineering
- Model selection
- Hyperparameter tuning

<b> Usage and Customisation: </b>
 Users can customise this project by experimenting with different models, feature engineering techniques, and hyperparameter tuning strategies. Additionally, they can apply the learned techniques to other financial prediction tasks or explore more advanced time series analysis methods.
