# 📊 Bitcoin Sentiment × Trader Behaviour Analysis

### Data Science Internship Assignment — Primetrade.ai  
**Author:** Omkar Thakur  

---

## 🚀 Objective
Analyze how Bitcoin market sentiment (Fear vs Greed) impacts trader behavior and performance on Hyperliquid.

---

## 📁 Dataset
- Bitcoin Fear & Greed Index
- Hyperliquid Historical Trader Data (~79K cleaned trades)

---

## ⚙️ Methodology

### Data Preparation
- Cleaned and normalized datasets
- Converted timestamps to daily level
- Merged sentiment with trading activity
- Created key metrics:
  - Daily PnL
  - Win rate
  - Trade frequency
  - Position size
  - Long/Short ratio

---

## 📊 Key Findings

### 1. Fear Days Outperform Greed Days
- Fear Avg PnL: **$9,387**
- Greed Avg PnL: **$5,415**

👉 Traders perform better during fear-driven volatility.

---

### 2. Panic Trading Behavior
- More trades during Fear (**85 vs 57/day**)
- Smaller position sizes
- Lower win rate

👉 Indicates emotional overtrading.

---

### 3. Greed Leads to Large Drawdowns
- Greed drawdown significantly higher

👉 Overconfidence → poor risk management

---

## 📈 Visualizations

| Analysis | Description |
|--------|------------|
| PnL Comparison | Fear vs Greed |
| Behavioral Trends | Trade frequency & size |
| Distribution | Position size spread |

---

## 🤖 Model (Bonus)
- Random Forest classifier
- Predict next-day profitability
- Used sentiment + behavioral features

---

## 💡 Strategy Recommendations

### 1. Reduce Overtrading During Fear
Avoid panic-driven frequent trades.

### 2. Control Risk During Greed
Use stop-loss / position sizing to prevent large losses.

### 3. Use Sentiment Shifts
Transition from Fear → Greed can signal opportunity.

---

## 🛠️ Tech Stack
- Python (Pandas, NumPy)
- Visualization (Matplotlib, Seaborn)
- ML (Scikit-learn)

---

## ▶️ How to Run

```bash
pip install -r requirements.txt
python src/main.py
