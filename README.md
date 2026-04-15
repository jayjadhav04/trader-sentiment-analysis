# 📊 Trader Performance vs Market Sentiment Analysis

## 📌 Objective

Analyze how market sentiment (Fear/Greed) impacts trader performance and behavior using real trading data.

---

## 📂 Dataset

* Bitcoin Fear & Greed Index
* Historical Trader Data (Hyperliquid)

---

## ⚙️ Approach

1. Data Cleaning & Preprocessing
2. Feature Engineering (PnL, Win Rate, Trade Size, Frequency)
3. Exploratory Data Analysis
4. Trader Segmentation
5. Behavioral Clustering
6. Insight Extraction
7. Strategy Recommendations

---

## 📊 Key Insights

* Extreme Greed shows highest win rate (~46%) and best performance
* Fear conditions provide higher average PnL than Greed (non-obvious insight)
* Traders take larger positions during Fear → higher risk
* Infrequent traders outperform frequent traders in Greed markets
* Overtrading and large position sizes reduce performance

---

## 🚀 Strategy Recommendations

* Reduce trade frequency during Greed to improve efficiency
* Limit position size during Fear to control risk
* Increase exposure in bullish markets with strict risk management
* Avoid overtrading and excessive risk-taking behavior

---

## 📌 Conclusion

* Market sentiment strongly influences trader performance
* Fear markets offer hidden opportunities
* Risk management and discipline matter more than market direction

---

## 🛠️ How to Run

```bash
pip install pandas matplotlib seaborn scikit-learn
jupyter notebook analysis.ipynb
```

---

## 📁 Project Structure

```
analysis.ipynb → Main analysis notebook  
images/ → Charts used in analysis  
```
