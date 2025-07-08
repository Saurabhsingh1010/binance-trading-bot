# Binance Futures Crypto Trading Bot (Testnet)

##  Developer: Saurabh Singh

This is a Python-based Binance USDT-M Futures trading bot built for the hiring assignment.

It supports:

- ✅ Market Orders
- ✅ Limit Orders
- ✅ Stop-Market Orders (Bonus)
- ✅ Secure API handling via `.env`
- ✅ Command-line interface
- ✅ Logging of all actions
- ✅ Error handling and user input validation

---

## 🔧 Technologies Used

- Python 3.x
- python-binance
- python-dotenv
- Binance Testnet

---

##  Folder Structure

```
saurabh_binance_bot/
│
├── bot.log
├── README.md
├── report.pdf
└── src/
    ├── basic_bot.py
    ├── market_orders.py
    ├── limit_orders.py
    └── advanced/
        └── stop_limit.py
```

---

##  .env File (DO NOT upload this)

```
API_KEY="your_api_key_here"
API_SECRET="your_api_secret_here"
```

---

##  How to Run

### 1. Install Dependencies

```
pip install python-binance python-dotenv
```

### 2. Create `.env` file with your Testnet API key & secret

### 3. Run Market Order

```
python src/market_orders.py BTCUSDT BUY 0.01
```

### 4. Run Limit Order

```
python src/limit_orders.py BTCUSDT SELL 0.01 62000
```

### 5. Run Stop-Market Order (Bonus)

```
python src/advanced/stop_limit.py BTCUSDT BUY 0.01 80000
```

---

##  Logging

All activity is saved in `bot.log` file.

---


