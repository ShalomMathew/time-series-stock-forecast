# Week 1 Notes: Time Series Analysis and Forecasting for Stock Market

## Overview
In the first week, the primary focus was to understand the fundamentals of time series data, especially within the context of stock market analysis. The goal was to become familiar with the nature of financial time series, key components, and data sources.

## Key Concepts Studied
- **Time Series Data:** A sequence of data points recorded at consistent time intervals.
- **Components of Time Series:**
  - **Trend:** The long-term movement in the data.
  - **Seasonality:** Repeating patterns or cycles in fixed periods (e.g., daily, monthly, yearly).
  - **Noise/Residual:** Irregular fluctuations or random variations.
- **Stationarity:** A time series whose statistical properties like mean and variance are constant over time.
- **Autocorrelation:** Correlation of a signal with a delayed copy of itself, important for model selection.
- **Common Models:** Introduction to ARIMA, SARIMA, Prophet, and LSTM (to be studied in detail later).

## Data Collection
- Chose Yahoo Finance as the primary data source for historical stock prices.
- Downloaded historical stock data for Apple Inc. (AAPL) from January 2015 to December 2024 using the `yfinance` Python library.
- Dataset includes Open, Close, High, Low, and Volume at daily intervals.

## Next Steps
- Proceed with data preprocessing and visualization.
- Explore statistical properties and patterns within the dataset.
- Prepare the data for modeling by handling missing values and potential anomalies.

---

*Prepared by: [Shalom Mathew]*  
*Date: [18-05-2025]*  
