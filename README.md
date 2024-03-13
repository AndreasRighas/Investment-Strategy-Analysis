# Investment-Strategy-Analysis
This poject explores different investment strategies that involves both cryptocurrencies and traditional markets.

## Overview

The analysis includes historical price data for cryptocurrencies (Bitcoin, Ethereum, and Litecoin) and traditional assets (Gold and S&P 500). The primary goal is to understand the trends and patterns in the market and evaluate the performance of various investment scenarios with the best return on investment.

## Key Features

- Fetches historical cryptocurrency price data from CoinGecko API and traditional financial data from Yahoo Finance.
- Calculates monthly returns for cryptocurrencies (Bitcoin, Ethereum, and Litecoin).
- Identifies positive monthly return periods for each cryptocurrency.
- Records cryptocurrency prices and dates for further analysis.
- Simulates monthly investments for different amounts in Bitcoin, Ethereum, and Litecoin.
- Compares investment strategies for cryptocurrencies, Gold, and S&P 500.
- Visualizes trends, balances, and cumulative investments over time.
- Identifies the best ROI

## Data Sources

- Cryptocurrency data: CoinGecko API
- Traditional financial data: Yahoo Finance (S&P 500 and Gold)

## Analysis

### Cryptocurrency Trends and Investments

The project analyzes the historical trends of Bitcoin, Ethereum, and Litecoin. Monthly returns are calculated, and positive return periods are identified. The code simulates different monthly investments in cryptocurrencies, providing insights into how these investments would perform over time.

### Traditional Financial Assets

The analysis extends to traditional financial assets, including Gold and S&P 500. Monthly investments are simulated, and the cumulative balances are compared over time.

### Visualization

The code uses Matplotlib and Seaborn for visualization. Line charts depict the historical prices of cryptocurrencies, cumulative investment balances, and trends over time. The project aims to provide a visual representation of investment strategies and their outcomes.

## Prerequisites

- Python 3.9
- Required Python packages: pandas, yfinance, matplotlib, seaborn, requests, datetime

## Usage

1. Clone the repository:

```bash
git clone https://github.com/AndreasRighas/investment-strategy-analysis.git
cd investment-strategy-analysis
