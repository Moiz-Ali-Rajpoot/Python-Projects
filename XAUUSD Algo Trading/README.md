# 📈 XAU/USD Algorithmic Trading Analysis — Python

> **Gold (XAU) Price Analysis & Momentum-Based Algorithmic Trading Strategy** — Built with Python using `yfinance`, `pandas`, and `Plotly` — fetching live market data, engineering trading signals, and visualizing Buy/Sell opportunities with interactive charts.

---

## 🗂️ Overview

This project explores **algorithmic trading strategy development** for Gold (XAU/USD) using Python. It fetches real-time and historical price data from Yahoo Finance, engineers a **momentum-based trading indicator**, generates automated **Buy and Sell signals**, and visualizes the full strategy with interactive Plotly charts.

---

## 📊 What This Notebook Covers

### 1. 📥 Live Market Data Extraction
- Fetches **6 months of Gold Futures (GC=F)** and **GLD ETF** price data directly from Yahoo Finance using `yfinance`
- Data includes Open, High, Low, Close, Volume, Dividends, and Stock Splits

### 2. 📉 Candlestick & Price Visualization
- Interactive **candlestick chart** of XAU/USD price movement built with `Plotly`
- Close price line chart overlaid with momentum indicators

### 3. ⚙️ Momentum Trading Strategy
- **Momentum Calculation** — 5-period percentage change in closing price
- **Signal Generation:**
  - 🟢 **Buy Signal** — Momentum exceeds `+1%` threshold (▲ triangle markers)
  - 🔴 **Sell Signal** — Momentum drops below `-1%` threshold (▼ triangle markers)
- Signals plotted directly on the price chart for visual backtesting

### 4. 📊 Dual-Panel Interactive Dashboard
- **Top Panel** — GLD price line chart with Buy (green ▲) and Sell (red ▼) signal markers
- **Bottom Panel** — Momentum indicator line (orange) showing the raw momentum values over time
- Built with `plotly.subplots` using shared x-axis for synchronized navigation

---

## 🛠️ Libraries & Tools

| Library | Purpose |
|---|---|
| `yfinance` | Live & historical market data from Yahoo Finance |
| `pandas` | Data manipulation, momentum calculations, signal logic |
| `plotly.graph_objects` | Candlestick charts, line charts, signal markers |
| `plotly.subplots` | Dual-panel layout (Price + Momentum) |
| `plotly.express` | Supplementary visualizations |

---

## ▶️ How to Run

```bash
# Install dependencies
pip install yfinance pandas plotly

# Run the notebook
jupyter notebook XAU_Algo_Trading.ipynb
```

---

## 💡 Key Concepts Demonstrated

- 📡 **Live financial data extraction** via API using `yfinance`
- 📐 **Feature engineering** — computing momentum from price percentage change
- 🔁 **Algorithmic signal generation** using conditional logic on financial indicators
- 📊 **Interactive financial charting** with Plotly — candlesticks, markers, dual-axis subplots
- 💹 **Quantitative trading strategy** — momentum-based Buy/Sell decision framework

---

> 📌 **Note:** This project is built for **educational and practice purposes only**. It is not financial advice. Trading signals generated here are based on a simplified momentum model and are not intended for live trading use.
