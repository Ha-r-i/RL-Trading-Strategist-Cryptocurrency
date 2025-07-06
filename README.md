# RL-Trading-Strategist-Cryptocurrency# 🧠 RL-Based Ethereum Trading Strategist

A Reinforcement Learning (RL) based cryptocurrency trading strategist focused on Ethereum (ETH), using historical price data and live updates via web scraping.

## 🚀 Project Overview

This project explores the application of Reinforcement Learning algorithms to develop an autonomous trading bot for Ethereum. It learns to make buy, sell, or hold decisions based on historical price patterns and simulated rewards.

Key components:
- Historical data-driven training
- Real-time web scraping for ETH prices
- Strategy testing using simulated environments
- Performance comparison of various RL and heuristic models

---

## 📊 Technologies & Libraries

- Python, Jupyter Notebook
- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `requests`, `BeautifulSoup` (Web scraping)
- `gym`, `stable-baselines3`, `tensorflow` or `torch`
- `scikit-learn` (for baseline ML models)

---

## 🕸️ Web Scraping Module

ETH/USD price data is scraped from trusted public sources such as:

- [CoinMarketCap](https://coinmarketcap.com/)
- [Yahoo Finance](https://finance.yahoo.com/)
- Using `requests` and `BeautifulSoup`

Scraped data is cleaned and appended to historical datasets in real-time during inference.

---

## 🤖 Reinforcement Learning Algorithms Used

Implemented and compared the following agents:

| Algorithm        | Description                              |
|------------------|------------------------------------------|
| DQN              | Deep Q-Learning with experience replay   |
| PPO              | Proximal Policy Optimization             |
| A2C              | Advantage Actor-Critic                   |
| Random           | Random policy baseline                   |
| Rule-Based       | Simple SMA/EMA crossover strategy        |

Each agent is trained on a custom OpenAI Gym environment modeling a crypto trading simulation.

---

## 📈 Strategy Evaluation

Metrics tracked:
- Total profit/loss
- Sharpe Ratio
- Win rate
- Average holding time
- Drawdowns

Visualizations include:
- Portfolio value over time
- Trade decisions marked on price chart

---

## 🗂️ Project Structure


---

## 📌 Future Work

- Add LSTM-based feature extraction
- Include other cryptocurrencies (BTC, ADA)
- Integrate with Binance testnet for real-time trading

---

## 🧑‍💻 Author

- Hari Balan K – [GitHub Profile](https://github.com/Ha-r-i)

---

## ⚖️ License

This project is licensed under the MIT License.
