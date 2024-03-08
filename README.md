

# Crypto-Portfolio-Optimization-and-Risk-Analysis

This repository contains the implementation of a machine learning-driven system for cryptocurrency portfolio optimization. The project aims to dynamically adjust portfolio allocations to maximize returns and minimize risks based on predictive analytics.

## Project Overview

The goal of this project is to develop a robust system that can forecast future cryptocurrency price movements and optimize portfolio allocations accordingly. It leverages historical price data from CryptoGecko and Yahoo Finance, focusing on the top 20 cryptocurrencies by market capitalization.

## Key Features

- **Data Collection**: Scripts to fetch historical data for the top 20 cryptocurrencies from CryptoGecko and Yahoo Finance.
- **Predictive Modeling**: Implementation of various machine learning models including ARIMA, LSTM, and XGBoost to predict future price movements with an emphasis on minimizing RMSE.
- **Optimization Algorithm**: Dynamic allocation strategy using techniques like the Kelly Criterion and Mean-Variance Optimization, tailored for cryptocurrency portfolios.
- **Risk Management**: Incorporates risk management measures such as setting maximum exposure limits and stop-loss strategies.
- **Backtesting Framework**: Evaluation of the portfolio's performance over time against historical data, considering transaction costs and market slippage.
- **Real-Time Data Pipeline and Monitoring System**: Infrastructure to ingest real-time data and monitor portfolio performance, enabling timely adjustments.

## Installation

1. Clone this repository:
git clone https://github.com/yourusername/crypto-portfolio-optimization.git
