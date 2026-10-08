# quant-trading-101
My first quantitative trading backtest using Python, Pandas, and YFinance.

## Overview
This project is a Python-based backtest of a 50/200-day moving average strategy applied across a multi-asset portfolio (SPY, QQQ, TLT, GLD).

## Features
- Downloads historical market data using `yfinance`.
- Calculates moving averages to generate buy/sell signals.
- Applies Risk Parity (inverse volatility) position sizing.
- Calculates professional performance metrics: CAGR, Sharpe Ratio, and Max Drawdown.

## Key Findings
- The Risk Parity portfolio drastically reduced the maximum drawdown compared to a standard Buy & Hold strategy.
- Transaction costs were accounted for to simulate realistic trading.

## Technologies Used
- Python
- Pandas, NumPy
- Matplotlib
- Google Colab
