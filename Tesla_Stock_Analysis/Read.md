# Tesla Stock Analysis

This project involves the analysis and forecasting of Tesla's stock price using multiple machine learning and statistical methods. The analysis includes time series forecasting, technical analysis, risk management, and event analysis to better understand the stock's trends, volatility, and key relationships.

## Key Features

- **Time Series Forecasting:**
  - Used **Auto-ARIMA** (MSE: 603.36), **SARIMA** (MSE: 603.36), and **LSTM** (MSE: 1246.08) to predict Tesla's stock price.
  
- **Risk Management:**
  - Implemented **Value at Risk (VaR)** at a **95% confidence** level to assess potential losses.

- **Technical Analysis:**
  - Calculated and visualized **10-day** and **50-day moving averages (MA)** to identify trends and potential crossovers.

- **Event Analysis:**
  - Integrated key **events** (e.g., product announcements, earnings releases) to assess their impact on stock price.

- **Visualizations:**
  - Created various visualizations such as **rolling statistics**, **autocorrelation plots**, **correlation heatmaps**, **moving averages**, and more.

## Installation

Clone the repository:

   ```bash
   git clone https://github.com/Anonymous143w/Tesla-Stock-Analysis.git
```
## Acknowledgements
- **Learn Some basic Trading Technical Analysis** like Indicators (MA, VWAP, ATR, RSI) & Candlesticks, Chart and Breckout Patterns etc. 
- **Stock Data:** Retrieved from **Yahoo Finance** using the `yfinance` library.
- **Forecasting Models:** The Auto-ARIMA, SARIMA, and LSTM models were implemented based on standard time series forecasting techniques.
- **Technical Analysis:** Moving averages and other technical indicators were calculated and visualized using **Matplotlib** and **Seaborn**.
- **Risk Management:** Value at Risk (VaR) calculated using historical return data for financial analysis.
