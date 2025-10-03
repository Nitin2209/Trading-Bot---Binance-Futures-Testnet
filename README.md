# Simplified Trading Bot - Binance Futures Testnet

A simplified Python trading bot to place market and limit orders on Binance Futures Testnet (USDT-M).  

---

# Features

- Place **Market Orders** (Buy/Sell)
- Place **Limit Orders** (Buy/Sell)
- Logs all API requests, responses, and errors in logs/trading_bot.log
- Simple Command-Line Interface (CLI)
- Optional: Can be extended with Stop-Limit, OCO, or other advanced order types

---

# Prerequisites

- Python 3.8+
- Binance Futures Testnet account ([https://testnet.binancefuture.com](https://testnet.binancefuture.com))
- Binance Testnet API Key & Secret

---

# Installation

1. **Clone the repository**
bash
git clone https://github.com/yourusername/binance-trading-bot-testnet.git
cd binance-trading-bot-testnet

2. **Create a virtual environment**
python -m venv venv
venv\Scripts\activate          # Windows

3. **Install dependencies**
pip install -r requirements.txt
python-binance

