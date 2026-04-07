# Stock Market Analysis
### Post-COVID Recovery to 2026 — Tech Giants & S&P 500

![Python](https://img.shields.io/badge/Python-3.13-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![License](https://img.shields.io/badge/License-MIT-green)

---

## Project Overview

End-to-end stock market analysis of Apple, Tesla, Nvidia and S&P 500
from 2015 to March 2026 — including technical indicators,
volatility analysis, correlation and LSTM price prediction.

---

## Project Structure

    stock-market-analysis/
    │
    ├── stock_market_analysis.ipynb   # Main notebook
    ├── requirements.txt              # Dependencies
    └── README.md                     # Project documentation

---

## Project Steps

| Step | Section |
|------|---------|
| 1 | Data Collection — yfinance |
| 2 | Data Cleaning |
| 3 | Exploratory Analysis |
| 4 | Technical Indicators (RSI, MACD, Bollinger Bands) |
| 5 | COVID Impact Analysis |
| 6 | Correlation Analysis |
| 7 | Volatility Analysis |
| 8 | LSTM Price Prediction |
| 9 | Trend Detection |
| 10 | Dashboard |
| 11 | Insights & Recommendations |

---

## Key Results

| Ticker | Total Return | Sharpe Ratio | LSTM R2 |
|--------|-------------|--------------|---------|
| AAPL | +918.5% | 0.86 | 0.894 |
| TSLA | +2,330.0% | 0.78 | 0.943 |
| NVDA | +34,097.7% | 1.32 | 0.646 |
| SPY | +271.5% | 0.75 | 0.901 |

---

## Tech Stack

| Tool | Usage |
|------|-------|
| Python 3.13 | Core language |
| pandas / numpy | Data manipulation |
| matplotlib / seaborn | Visualization |
| yfinance | Stock data download |
| scikit-learn | Preprocessing & metrics |
| TensorFlow / Keras | LSTM Deep Learning |
| Jupyter Notebook | Development environment |

---

## Getting Started

    # 1. Clone the repository
    git clone https://github.com/BryolTene/stock-market-analysis.git

    # 2. Create virtual environment
    python3 -m venv stock_analysis
    source stock_analysis/bin/activate

    # 3. Install dependencies
    pip install -r requirements.txt

    # 4. Launch Jupyter
    jupyter notebook

---

## Dataset

Data is automatically downloaded from Yahoo Finance via yfinance.
No manual download required.

Period : January 2015 to March 31, 2026
Assets : AAPL, TSLA, NVDA, SPY

---

## Author

bryolt
GitHub : https://github.com/BryolTene

---

## License
MIT License
