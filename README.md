# Algorithmic Trading Strategy – SMA Crossover Demo

An interactive **Simple Moving Average (SMA) Crossover** strategy simulator built with pure HTML, CSS, and JavaScript (Chart.js).

## 🚀 Live Demo

**[Click here to view the live website](https://mayank403.github.io/algorithmic-trading-strategy/)**

> Note: It may take 1–2 minutes after enabling GitHub Pages for the site to go live.

## 📊 Features

- Interactive price chart with **Buy** and **Sell** signals
- Adjustable parameters:
  - Fast SMA period
  - Slow SMA period
  - Starting capital
  - Number of trading days
- Performance metrics:
  - Total Return (%)
  - Final Equity
  - Win Rate
  - Number of Trades
- Clean dark theme UI
- Fully client-side (no backend required)

## 💡 How the Strategy Works

1. **Buy Signal** → When the Fast SMA crosses **above** the Slow SMA (bullish crossover)
2. **Sell Signal** → When the Fast SMA crosses **below** the Slow SMA (bearish crossover)
3. The strategy stays in cash when no position is open
4. Price data is generated using a random walk to simulate realistic market movement

## 🛠️ How to Run Locally

1. Download or clone this repository
2. Open `index.html` in any modern browser

```bash
git clone https://github.com/mayank403/algorithmic-trading-strategy.git
cd algorithmic-trading-strategy
# Just open index.html
```

## 📁 Project Structure

```
algorithmic-trading-strategy/
├── index.html      # Main application
├── README.md       # This file
└── .nojekyll       # Required for GitHub Pages
```

## 📝 Tech Stack

- HTML5 + CSS3
- Vanilla JavaScript
- [Chart.js](https://www.chartjs.org/) (via CDN)

## ⚙️ Customization Ideas

You can easily extend this project by adding:
- RSI / MACD / Bollinger Bands strategies
- Equity curve chart
- Position sizing & risk management
- Real historical data (via API)

## 👤 Author

Created by [mayank403](https://github.com/mayank403)

---

⭐ If you find this useful, please give the repository a star!
