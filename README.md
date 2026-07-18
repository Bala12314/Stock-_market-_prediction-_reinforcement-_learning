
# 📈 Stock Market Prediction using Reinforcement Learning

## Overview

This project explores the use of **Reinforcement Learning (RL)** for stock market trading and prediction. The objective is to train intelligent agents capable of making buy, sell, and hold decisions based on historical stock market data and technical indicators.

The project analyzes three major Indian stocks:

* TCS (Tata Consultancy Services)
* Reliance Industries
* MRF (Madras Rubber Factory)

Using RL algorithms, the model learns trading strategies and compares its performance against traditional buy-and-hold benchmark strategies.

---

## 🚀 Features

* Historical stock data collection using Yahoo Finance
* Technical indicator generation and analysis
* Reinforcement Learning-based trading environment
* Performance comparison with benchmark strategies
* Correlation-based feature selection
* Multiple training and testing experiments
* Visualization of stock prices, returns, and indicators

---

## 📊 Technical Indicators Used

The project incorporates several popular technical indicators:

* Efficiency Ratio (ER)
* Relative Strength Index (RSI)
* Weighted Moving Average (WMA)
* Stochastic Oscillator (STOCH)
* Positive Volume Index (PVI)
* Moving Averages (50-day & 100-day)
* Volume-based indicators
* Return calculations

These indicators form the state space observed by the RL agent.

---

## 🧠 Reinforcement Learning Approach

The RL agent interacts with a custom trading environment and learns to maximize cumulative rewards.

### Actions

* Buy (Long)
* Sell (Short)
* Hold

### Objective

Maximize portfolio returns while outperforming a buy-and-hold investment strategy.

---

## 🛠️ Technologies Used

* Python
* Reinforcement Learning
* Stable-Baselines3
* A2C (Advantage Actor-Critic)
* Pandas
* NumPy
* Matplotlib
* mplfinance
* Yahoo Finance API (yfinance)
* Scikit-Learn

---

## 📈 Workflow

1. Collect historical stock data.
2. Calculate technical indicators.
3. Create trading environment.
4. Train RL agent.
5. Evaluate performance.
6. Compare against benchmark strategy.
7. Analyze actions and returns.

---

## 📋 Results

### Key Findings

* RL agents frequently outperformed traditional buy-and-hold strategies.
* TCS showed the most consistent performance across experiments.
* Feature selection using highly correlated indicators improved training efficiency.
* Models performed well on training data but showed signs of overfitting on unseen market conditions.

---

## 📂 Project Structure

```text
Stock-Market-Prediction-RL/
│
├── Stock market prediction- Reinforcement Learning.ipynb
├── README.md
└── assets/
    └── project-banner.png
```

---

## ▶️ Installation

```bash
git clone https://github.com/yourusername/Stock-Market-Prediction-RL.git

cd Stock-Market-Prediction-RL

pip install -r requirements.txt
```

---

## 📌 Future Improvements

* Deep Q-Network (DQN)
* PPO Reinforcement Learning
* LSTM + RL Hybrid Models
* Multi-stock portfolio optimization
* Risk-adjusted reward functions
* Real-time trading simulation

---

## 📚 References

* Stable-Baselines3 Documentation
* Yahoo Finance API
* Reinforcement Learning Research Papers
* Dynamic Stock-Decision Ensemble Strategy Based on Deep Reinforcement Learning

---

## 👨‍💻 Author

**Abhishek Kaushal**

* Python Developer
* AI & Data Science Enthusiast
* Machine Learning and Reinforcement Learning Practitioner



