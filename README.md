# 📊 Trader Performance vs Market Sentiment Analysis

## 🚀 Quick Summary

This project analyzes how market sentiment (Fear/Greed) affects trader behavior and performance.

👉 **Key finding:** Fear markets often provide higher average profit than Greed, while overtrading reduces performance.
👉 **Outcome:** Data-driven strategies to improve trading efficiency and risk control.

---

## 📌 Objective

Analyze how market sentiment impacts:

* Trader performance (PnL, win rate)
* Trading behavior (frequency, trade size)
* Risk patterns

---

## 📂 Dataset

* Bitcoin Fear & Greed Index
* Historical Trader Data (Hyperliquid)

---

## ⚙️ Approach

1. Data Cleaning & Preprocessing
2. Timestamp Alignment (daily level)
3. Feature Engineering:

   * Win Rate
   * Average PnL
   * Trade Size
   * Trade Frequency
4. Exploratory Data Analysis (EDA)
5. Trader Segmentation (Frequent vs Infrequent)
6. Behavioral Clustering (K-Means)
7. Insight Extraction & Strategy Design

---

## 📊 Sample Outputs

### 🔹 Win Rate by Sentiment

![Win Rate](images/win_rate.png)

### 🔹 Trade Size by Sentiment

![Trade Size](images/trade_size.png)

### 🔹 PnL by Frequency

![PnL Frequency](images/pnl_requency.png)

---

## 🔍 Key Insights

* Extreme Greed shows highest win rate (~46%) and strongest performance
* Fear markets provide higher average PnL than Greed (non-obvious insight)
* Traders take larger positions during Fear → increased risk
* Infrequent traders outperform frequent traders in Greed markets
* Overtrading and large position sizes reduce overall performance

---

## 🚀 Strategy Recommendations

### Strategy 1: Control Overtrading

* Reduce trade frequency during Greed phases
* Improves efficiency and profitability

---

### Strategy 2: Risk Control in Fear Markets

* Limit position size during Fear conditions
* Reduces exposure to volatility

---

### Strategy 3: Controlled Participation in Bull Markets

* Increase exposure during Extreme Greed with strict risk management
* Captures trend opportunities while limiting risk

---

### Strategy 4: Avoid Aggressive Trading Behavior

* Limit excessive trading and large position sizing
* Improves consistency and long-term performance

---

## 📌 Conclusion

* Market sentiment significantly influences trader performance
* Fear markets offer hidden profit opportunities
* Discipline and risk control outperform aggressive trading

👉 Successful trading depends more on behavior than market direction

---

## 🛠️ How to Run

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook analysis.ipynb
```

---

## 📁 Project Structure

```
analysis.ipynb        → Main analysis notebook  
images/               → Visual outputs  
Analysis Report.pdf   → Final summarized report  
README.md             → Project overview  
```

---

## 📂 Dataset Access

Due to dataset size, raw files are hosted on Google Drive:

👉 [Download Dataset](https://drive.google.com/drive/folders/1xaPsqLrGZbE3IFlYAb1CzIuOx4XJsoSc)

Includes:
- Fear & Greed Index dataset  
- Historical Trader Data  


---
