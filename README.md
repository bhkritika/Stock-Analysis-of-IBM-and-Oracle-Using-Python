# Stock Analysis of IBM and Oracle Using Python
 
## Overview

This project performs a comprehensive analysis of IBM and Oracle stock prices. The analysis includes trend analysis, volatility measurement, forecasting, technical indicators, correlation analysis, and sentiment analysis of news articles. The goal is to derive insights from historical stock data and predict future trends.

## Objectives

1. **Trend Analysis**: Identify historical price trends and patterns.
2. **Volatility Measurement**: Assess stock price volatility and associated risk.
3. **Forecasting**: Evaluate different forecasting models for predicting future stock prices.
4. **Technical Indicators**: Analyze technical indicators to derive trading signals.
5. **Correlation Analysis**: Understand relationships between stock metrics and their correlations.
6. **Sentiment Analysis**: Examine the impact of news sentiment on stock prices.

## Analysis

1. **Plot Close Price**: Visualize the closing price of IBM and Oracle stocks.
2. **Calculate Moving Averages**: Compute and plot moving averages for trend analysis.
3. **Calculate and Plot Daily Returns**: Analyze daily returns to understand stock performance.
4. **Calculate and Plot Volatility**: Measure and visualize volatility to assess risk.
5. **Rolling Mean and Standard Deviation**: Examine rolling statistics for trends and fluctuations.
6. **Technical Indicators**: Implement indicators such as RSI and Bollinger Bands.
7. **Correlation Analysis**: Analyze correlations between stock metrics.
8. **Candlestick Chart**: Create candlestick charts for detailed price movements.
9. **Histogram of Returns**: Plot histograms to visualize return distributions.
10. **Exponential Moving Average (EMA) Analysis**: Evaluate the EMA for trend signals.
11. **Bollinger Bands Analysis**: Analyze Bollinger Bands for market volatility.
12. **Monte Carlo Simulation**: Simulate stock price movements to assess potential future scenarios.
13. **Value at Risk (VaR) Calculation**: Compute VaR to estimate potential losses.
14. **Forecasting with Prophet**: Use the Prophet model for future price forecasting.
15. **GARCH Model Analysis**: Apply GARCH models to assess volatility clustering.
16. **Compare Forecast Models**: Compare the performance of different forecasting models.
17. **Sentiment Analysis of News Articles**: Analyze the impact of news sentiment on stock prices.
18. **Heatmap of Stock Correlations**: Visualize correlations between different stock metrics.
19. **Box Plot of Stock Prices**: Create box plots to examine price distributions.
20. **QQ Plot of Stock Returns**: Generate QQ plots to assess return distributions.
21. **Lag Plot Analysis**: Analyze lag plots to identify patterns and relationships.
22. **Time Series Decomposition**: Decompose time series to understand seasonal and trend components.
23. **Price vs Volume Scatter Plot**: Examine the relationship between price and trading volume.

## Conclusion

1. **Historical Trends**: Key trends and patterns were identified, providing insights into potential trading signals.
2. **Volatility**: Volatility analysis highlighted the risk levels associated with stock prices.
3. **Forecasting Models**: Various models (Exponential Smoothing, SARIMA, Prophet) were compared for forecasting accuracy.
4. **Technical Indicators**: Indicators like RSI and Bollinger Bands provided actionable market insights.
5. **Correlation**: Correlation analysis revealed important relationships between stock metrics.
6. **Sentiment Impact**: Sentiment analysis demonstrated the significant influence of news on stock prices.

## Future Work

1. **Enhance Data**: Incorporate additional financial and market data.
2. **Refine Models**: Improve forecasting accuracy with advanced modeling techniques.
3. **Expand Analysis**: Apply methods to other stocks or financial assets for broader insights.

## Getting Started

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/ibm-oracle-stock-analysis.git
    ```
2. Navigate to the project directory:
    ```bash
    cd ibm-oracle-stock-analysis
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4. Run the Jupyter notebook:
    ```bash
    jupyter notebook
    ```

## Dependencies

- pandas
- numpy
- matplotlib
- seaborn
- statsmodels
- fbprophet (for forecasting)
- arch (for GARCH models)
- textblob (for sentiment analysis)
- other relevant libraries