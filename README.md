# Quantitative-Projects
Five quantitative Projects in Python implementing quantitative analysis. Below is an explanation of the projects:

## Moving Average Crossover Algorithmic Trading Strategy
This project implements a basic algorithmic trading strategy based on the moving average crossover technique, allowing users to backtest and evaluate its effectiveness on historical stock price data. The strategy is designed to generate buy and sell signals using two moving averages (short-term and long-term) to identify potential entry and exit points.

Buy Signal: Triggered when the short-term moving average crosses above the long-term moving average, indicating a potential upward trend.
Sell Signal: Triggered when the short-term moving average crosses below the long-term moving average, indicating a possible downward trend.

<b> Features </b>
- Data Loading and Processing: Imports historical stock data for analysis and modelling.
- Moving Average Calculation: Calculates short-term and long-term moving averages to identify crossovers.
- Signal Generation: Detects crossover events to produce buy/sell signals.
- Backtesting Framework: Simulates the strategy on historical data to evaluate performance.
- Performance Metrics: Compares strategy returns against a simple buy-and-hold approach with cumulative returns.

<b> Usage and Customisation </b>
Users can adjust the parameters for short-term and long-term moving averages to explore how different settings impact performance. Additionally, this project provides a foundation for incorporating advanced features, such as stop-loss mechanisms, momentum indicators, and volatility filters.
