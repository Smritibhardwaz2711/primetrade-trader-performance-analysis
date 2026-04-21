# 📈 Trader Performance vs Market Sentiment Analysis  
### Primetrade.ai – Data Science / Analytics Intern Round-0 Assignment

> A data-driven study on how Bitcoin Fear & Greed sentiment impacts trader behavior, profitability, and risk-taking on Hyperliquid.
## 📊 Output Charts
![Output](https://github.com/Smritibhardwaz2711/primetrade-trader-performance-analysis/blob/8da9b843c9b0b572ee49f7306bda840585095f84/Output.png)
### Charts

### Trade Size USD Distribution
![Trade Size USD Distribution](https://github.com/Smritibhardwaz2711/primetrade-trader-performance-analysis/blob/8da9b843c9b0b572ee49f7306bda840585095f84/Trade%20size%20USD%20Distribution.png)
### PnL Distribution Fear vs Greed
![PnL Distribution](https://github.com/Smritibhardwaz2711/primetrade-trader-performance-analysis/blob/8da9b843c9b0b572ee49f7306bda840585095f84/PnL%20Distribution.png)

### Top 10 Traders by Total Closed PnL
![Top Traders](https://github.com/Smritibhardwaz2711/primetrade-trader-performance-analysis/blob/8da9b843c9b0b572ee49f7306bda840585095f84/Top%2010%20Traders.png)

### Confusion Matrix
![Confusion Matrix](https://github.com/Smritibhardwaz2711/primetrade-trader-performance-analysis/blob/8da9b843c9b0b572ee49f7306bda840585095f84/confusion%20matrix.png)

### frequent vs infrequent Traders
![frequent vs infrequent Traders](https://github.com/Smritibhardwaz2711/primetrade-trader-performance-analysis/blob/8da9b843c9b0b572ee49f7306bda840585095f84/frequent%20vs%20infrequent%20Traders.png)

### Trade By count Sentiment
![Trade By count Sentiment.png](https://github.com/Smritibhardwaz2711/primetrade-trader-performance-analysis/blob/8da9b843c9b0b572ee49f7306bda840585095f84/Trade%20By%20count%20Sentiment.png)

### Feature Importance - Next Day Profutability
![Feature Importance - Next Day Profutability](
https://github.com/Smritibhardwaz2711/primetrade-trader-performance-analysis/blob/8da9b843c9b0b572ee49f7306bda840585095f84/Feature%20Importance%20-%20Next%20Day%20Profutability.png)

### long/short Bias By Sentiment
![long/short Bias By Sentiment](https://github.com/Smritibhardwaz2711/primetrade-trader-performance-analysis/blob/8da9b843c9b0b572ee49f7306bda840585095f84/long.png)

### trade by size sentiment
![trade by size sentiment](https://github.com/Smritibhardwaz2711/primetrade-trader-performance-analysis/blob/8da9b843c9b0b572ee49f7306bda840585095f84/trade%20by%20size%20sentiment.png)



## 👩‍💻 Candidate

**Smriti Kumari**  
Aspiring Data Analyst | Data Science Enthusiast | Python Developer  


## 🎯 Objective

The purpose of this project is to analyze whether market sentiment (**Fear / Greed**) influences trader decision-making and performance.

Using real historical trader data and Bitcoin sentiment signals, this project uncovers patterns that can support smarter trading strategies, trader segmentation, and predictive decision-making.


## 📂 Datasets Used

### 1️⃣ Bitcoin Market Sentiment Dataset
- Date
- Classification (Fear / Greed)

### 2️⃣ Historical Trader Data (Hyperliquid)
Includes:

- Account
- Coin
- Execution Price
- Size USD
- Side (Long / Short)
- Closed PnL
- Fee
- Timestamp
- Position Details

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab / Jupyter Notebook


## 🔍 Project Workflow

###  Data Preparation
- Loaded both datasets
- Checked missing values & duplicates
- Cleaned timestamps
- Merged datasets on daily date level
- Created derived metrics

###  Metrics Built
- Daily PnL
- Win Rate
- Trade Frequency
- Average Trade Size
- Long / Short Ratio
- Risk Appetite Proxy (Size USD)

###  Exploratory Analysis
Compared trader behavior during:

- Fear Days
- Greed Days

### Trader Segmentation

Identified key trader groups:

- Frequent vs Infrequent Traders
- Consistent Winners vs Inconsistent Traders
- High Risk vs Low Risk Traders

### Predictive Modeling (Bonus)

Built a **Random Forest Classifier** to predict next-day trader profitability using:

- Sentiment
- Previous PnL
- Rolling Performance
- Trade Size
- Fees
- Win Rate

## 📊 Key Insights

### 📌 1. Greed Days Show Better Performance
Traders generally earned higher profits during Greed market sentiment.

### 📌 2. Fear Days Have Deeper Losses
Average losing trades were larger during Fear conditions.

### 📌 3. Larger Position Sizes During Greed
Risk appetite increased significantly when sentiment turned positive.

### 📌 4. Frequent Traders Outperformed Others
More active traders showed stronger cumulative profitability.

### 📌 5. Trader Quality Matters
Consistent profitable traders performed better across all regimes.


## 🤖 Machine Learning Result

| Model | Accuracy |
|------|----------|
| Random Forest Classifier | ~70% |

This suggests sentiment + behavior signals contain meaningful predictive power.



## 💡 Strategy Recommendations

### Strategy 1
During **Fear Days**, reduce position sizing and avoid overtrading.

### Strategy 2
During **Greed Days**, allow higher participation only for historically profitable traders.

### Strategy 3
Allocate more capital to consistent winners and reduce exposure to inconsistent traders.



## 📁 Repository Contents

```text
primetrade-trader-performance-analysis/
│── primetrade_trader_sentiment_analysis.ipynb
│── README.md
│── charts/
│── outputs/
