# Portfolio Management and Optimization

## Overview

This project implements a portfolio management and optimization system using Modern Portfolio Theory. It analyzes historical stock data, calculates various financial metrics, and determines an optimal portfolio allocation to maximize risk-adjusted returns.

## Features

- Data retrieval from Yahoo Finance API
- Calculation of daily returns and moving averages
- Visualization of stock performance and correlations
- Implementation of Modern Portfolio Theory
- Efficient frontier generation
- Portfolio optimization based on Sharpe ratio

## Prerequisites

- Python 3.x
- Required libraries: pandas, yfinance, matplotlib, seaborn, numpy

## Installation

1. Clone this repository: git clone https://github.com/Abhay06102003/Portfolio_Management_And_Optimization.git
2. Install the required libraries: pip install pandas yfinance matplotlib seaborn numpy

## Usage

1. Update the `tickers` list in the script with your desired stock symbols.
2. Adjust the `DAYS` and `AMOUNT` variables as needed.
3. Run the script: python portfolio_optimization.py

## Key Components

1. **Data Retrieval and Preprocessing**: The script downloads historical stock data using the yfinance library and preprocesses it for analysis.

2. **Visualization**:
- Line plots of adjusted close prices over time
- Moving average plots (50-day and 200-day)
- Volume traded bar charts
- Distribution of daily returns
- Correlation heatmap of stock returns

3. **Portfolio Optimization**:
- Calculation of expected returns and volatility
- Generation of random portfolios to identify the efficient frontier
- Optimization to maximize the Sharpe ratio

4. **Results**:
- Efficient frontier plot
- Optimal portfolio weights
- Suggested number of stocks to purchase based on the optimal allocation

## Results Interpretation

The script outputs:
- Visual representations of stock performance and relationships
- An efficient frontier plot showing risk-return tradeoffs
- Optimal portfolio weights for maximizing the Sharpe ratio
- Suggested stock quantities to purchase based on a given investment amount

## Contributing

Contributions to improve the project are welcome. Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Disclaimer

This tool is for educational purposes only. It does not constitute financial advice. Always conduct your own research and consult with a qualified financial advisor before making investment decisions.
