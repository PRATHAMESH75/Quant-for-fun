# 📈 EMA 50/200 Crossover Trading Strategy

This repository contains a Jupyter Notebook implementing a **technical trading strategy** based on the crossover of two Exponential Moving Averages (EMAs) — **EMA50** and **EMA200** — applied to real historical stock data (AAPL).

The strategy simulates trades by:
- **Buying** when EMA50 crosses above EMA200 (bullish crossover)
- **Selling** when EMA50 crosses below EMA200 (bearish crossover)
- Calculating **profit/loss** for each trade pair

---

## 📊 Features

- Load real AAPL stock data from a local CSV
- Filter by custom date range
- Calculate EMA50 and EMA200
- Detect bullish and bearish crossovers
- Simulate sequential trades
- Compute total and individual trade profits/losses
- Visualize price chart with:
  - Close Price
  - EMA lines
  - Buy and Sell signals (arrows)

---

## 📁 Files

| File Name                | Description                                |
|-------------------------|--------------------------------------------|
| `ema_crossover.ipynb`   | Jupyter Notebook containing full analysis  |
| `aapl.csv`              | Cleaned AAPL historical data               |


---

## ▶️ How to Use

1. Clone this repository or upload your notebook to GitHub.
2. Make sure `aapl.csv` is placed in the same directory.
3. Run the notebook.
4. Enter your desired date range when prompted.
5. View results and export the trade table if needed.

---

## 📦 Requirements

- Python 3.x
- pandas
- matplotlib
- Jupyter Notebook

To install:
```bash
pip install pandas matplotlib notebook
