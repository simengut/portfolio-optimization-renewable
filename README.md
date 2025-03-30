# Portfolio Optimization Analysis

This project implements various portfolio optimization strategies including:
- Markowitz Mean-Variance Optimization
- Risk Parity Portfolio
- Equal Weighted Portfolio

## Features
- Historical data analysis of clean energy ETFs
- Portfolio optimization using different strategies
- Performance comparison and risk metrics
- Monte Carlo simulations for risk assessment
- GARCH volatility modeling

## Data Sources
- CRSP database for historical price data
- Clean energy ETFs including ICLN, PBW, QCLN, IXC, VDE, and XLE

## Requirements
- Python 3.x
- pandas
- numpy
- cvxpy
- arch
- matplotlib
- seaborn

## Installation
1. Clone the repository
2. Install required packages:
```bash
pip install -r requirements.txt
```

## Usage
1. Set up your database connection
2. Run the analysis:
```python
python InitialAnalysis.py
```

## Results
The analysis provides:
- Optimal portfolio weights for different strategies
- Performance metrics (returns, volatility, Sharpe ratio)
- Risk metrics (VaR, CVaR)
- Portfolio visualization and comparison 