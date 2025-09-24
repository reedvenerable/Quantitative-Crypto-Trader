Quantitative Crypto Model

A Python framework for systematic cryptocurrency trading strategies with order book simulation, machine learning signal generation, and walk-forward backtesting. Includes risk controls, performance metrics, and a Streamlit dashboard for visualizing strategy results.

Features

Order book simulator with depth and execution cost modeling.

Execution strategies: TWAP, POV, aggressive, adaptive ML-based.

Feature engineering for returns, volatility, spreads, order book imbalance.

Machine learning forecasters (e.g., logistic regression, EMA-based).

Walk-forward backtesting with slippage and transaction costs.

Risk management overlays (volatility targeting, kill-switches, stop losses).

Performance metrics: Sharpe, Calmar, max drawdown, hit rate.

Interactive Streamlit dashboard for results and trade analysis.

Installation

Clone the repo and install dependencies:

git clone https://github.com/yourusername/quantitative-crypto-model.git
cd quantitative-crypto-model
pip install -r requirements.txt


Dependencies:

Python 3.10+

pandas, numpy, matplotlib

scikit-learn

streamlit

Usage

Run a backtest from the command line:

python quantitative_crypto_model.py --strategy twap --data data/binance.csv


Or start the dashboard:

streamlit run dashboard.py

Example Output

Equity curve plots with Sharpe/Calmar ratios.

Trade log with entry/exit points.

Dashboard view of signals, P&L attribution, and order execution.

(Insert screenshots here once you have them!)

Project Structure
quantitative_crypto_model.py   # Main framework
notebooks/                     # Jupyter notebooks for research
data/                          # Sample input data (CSV, OHLC, L2 order book)
dashboard.py                   # Streamlit dashboard
README.md                      # Project documentation
