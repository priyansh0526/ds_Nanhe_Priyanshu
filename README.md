# 📊 Trader Behavior vs Market Sentiment (Fear & Greed Analysis)
## 🧠 Project Overview

This project analyzes how trader behavior changes with overall market sentiment in the Bitcoin market. Using historical trading data and the Fear & Greed Index, the goal is to understand the relationship between profitability, risk, volume, and activity under different emotional market conditions such as Fear and Greed.

The analysis helps uncover hidden signals that can be used to design smarter and safer trading strategies in Web3 trading systems.

## 🎯 Objectives

* Analyze trader behavior using historical trade data.

* Merge trading metrics with market sentiment (Fear / Greed).

* Study how profitability, volume, and risk change with sentiment.

* Identify patterns that influence smarter trading strategies.

* Provide visual and statistical insights for decision-making.

# 📁 Project Structure
ds_<candidate_name>/

├── notebook_1.ipynb        

├── csv_files/

│     ├── fear_greed_index.csv

│     ├── historical_data.csv

│     ├── merged_sentiment_trades.csv

│     └── sentiment_summary.csv

├── outputs/

│     ├── avg_volume_by_sentiment.png

│     ├── total_pnl_by_sentiment.png

│     ├── winrate_by_sentiment.png

│     ├── activity_by_sentiment.png

│     └── risk_return_by_sentiment.png

├── ds_report.pdf       

└── README.md            

## 📊 Datasets

Two datasets are used:

### 1️⃣ Historical Trader Data (Hyperliquid)

* Contains:

* account

* symbol

* execution price

* size

* side (BUY/SELL)

* time

* closed PnL

* fees

### 2️⃣ Bitcoin Fear & Greed Index

* Contains:

* date

* classification (Fear / Greed)

This dataset provides daily market sentiment information.

## ⚙️ Tools & Libraries

* Python

* Pandas

* NumPy

* Matplotlib

* VS Code

## 🔄 Methodology

* Load and clean both datasets.

* Standardize column names and data types.

* Engineer features such as:

  * Notional Value

  * Net PnL

  * PnL Percentage

  * Win Rate

  * Trading Volume

* Aggregate trading behavior by day.

* Merge daily metrics with Fear/Greed sentiment.

* Compare Fear vs Greed using:

  * Volume

  * Profitability

  * Activity

  * Risk

* Visualize results and extract insights.

## ❓ Key Questions Answered

1. Do traders trade more during Fear or Greed?

2. Is profitability higher during Fear or Greed?

3. Does risk increase with market sentiment?

4. How does win rate change with sentiment?

5. Are traders more aggressive during Greed?

6. What hidden patterns can improve trading strategies?

## 📈 Insights

* Trading volume and activity increase during Greed periods.

* Profitability is generally higher during optimistic market conditions.

* Risk (PnL volatility) rises with Greed.

* Fear leads to cautious behavior but can cause panic losses.

* Sentiment-aware strategies can reduce exposure and improve returns.

## 🧩 Limitations

* Sentiment data is daily, while trades are intraday.

* Leverage information is limited.

* Market emotion is simplified into Fear/Greed only.

* Dataset period is finite.

## 🚀 Future Enhancements

* Add leverage and liquidation analysis.

* Build predictive models based on sentiment.

* Perform trader clustering.

* Apply time-series forecasting.

* Detect regime changes.


👤 Author

Nanhe Priyanshu

Data Science Candidate – PrimeTrade.ai Assignment
