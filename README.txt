# 📈 Stock Prediction Model

This project uses historical stock data to predict future returns, volatility, and risk-adjusted return (like Sharpe ratio).

---

## 🧠 Modules

- `data_collection.py`: Collects historical data for multiple companies
- `stock-prediction.py`: Applies machine learning to predict stock performance

---

## 🗂 Output Format

| Ticker | Predicted_Return | Volatility | Risk_Adjusted_Return |
|--------|------------------|------------|------------------------|
| AAPL   | 0.052            | 0.015      | 3.47                   |
| TSLA   | 0.032            | 0.020      | 1.60                   |

---

## 🛠 How to Use

```bash
pip install -r requirements.txt
python src/data_collection.py
python src/stock-prediction.py
