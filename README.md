# Crypto Portfolio Tracker

A beginner-friendly Python project that tracks cryptocurrency holdings and calculates profit/loss from a list of transactions.

## 📊 Features
- Build a portfolio dictionary from transaction data
- Track remaining quantity of each cryptocurrency
- Calculate profit/loss (PNL) based on today’s prices
- Compute average purchase price
- Filter purchases after a specific date using the `datetime` library

## 🛠️ Technologies Used
- Python 3
- Built-in libraries (`datetime`)

## 🚀 How It Works
1. Transactions are stored as a list of dictionaries:
   ```python
   {
       "symbol": "BTC",
       "type": "buy",
       "quantity": 0.7,
       "price": 27090.4,
       "date": "2022-03-07"
   }

