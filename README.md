Predictive Insights: Analyzing Asset Performance with Advanced Simulation Techniques

Project Objective
This project is designed to conduct a comprehensive analysis of the investment performance of various assets, including Bitcoin, Ethereum, S&P 500, and Gold. By leveraging historical price data from January 2020 to March 2024, the study aims to dive into the dynamics of these assets, examining their price movements and evaluating their performance from the perspectives of risk and return.

The analysis will focus on the calculation of key financial metrics to illuminate the risk-return trade-offs and the correlations between these assets. Additionally, the study will assess the impact of different monthly investment amounts like  10,
 50, and $100.

To enhance the robustness of the predictions about future market behaviors, both Long Short-Term Memory (LSTM) models and Monte Carlo simulations will be employed. These methodologies will be applied to determine the feasibility of predicting market trends based solely on date and price data, aiming to uncover deeper insights into the potential predictive power of these models within the complex landscape of financial markets.

The objective is to not only understand historical performance but also to explore the effectiveness of analytical techniques in forecasting future asset valuations, providing a valuable resource for strategic investment planning.
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
