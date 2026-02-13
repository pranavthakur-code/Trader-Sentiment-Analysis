# Trader Sentiment vs Trader Performance Analysis

## 📊 Project Overview

This project analyzes the relationship between Bitcoin market sentiment (Fear vs Greed) and trader performance on Hyperliquid.

The objective is to understand whether market sentiment influences trader behavior, profitability, leverage patterns, and trading frequency — and to derive actionable trading insights.

---

## 📁 Datasets Used

1. Bitcoin Market Sentiment (Fear/Greed Index)
2. Historical Trader Data (Hyperliquid)

---

## ⚙️ Methodology

### 1. Data Preparation
- Cleaned datasets
- Converted timestamps to daily level
- Merged trader data with sentiment data
- Checked missing values and duplicates

### 2. Feature Engineering
- Daily PnL per account
- Win rate
- Trade frequency per day
- Long/Short ratio
- Trade size segmentation

### 3. Analysis
- Compared performance during Fear vs Greed days
- Analyzed behavioral changes in trading activity
- Segmented traders by trade size and consistency

---

## 🔍 Key Insights

- Trading activity tends to increase during Greed periods.
- Profitability distribution varies between Fear and Greed days.
- High trade size accounts show larger PnL volatility.
- Behavioral bias (Long/Short) shifts depending on sentiment.

---

## 💡 Strategy Recommendations

1. Reduce position size during high Fear periods to manage downside risk.
2. Use momentum-based strategies during Greed phases.
3. Avoid overtrading during high-volatility sentiment periods.

---

## 📦 Repository Contents

- `Untitled12.ipynb` → Full analysis notebook
- README.md → Project documentation

---

## 🚀 How to Run

1. Open the notebook in Google Colab or Jupyter.
2. Upload the required datasets.
3. Run cells sequentially.

---

## 📌 Author

Pranav Thakur

