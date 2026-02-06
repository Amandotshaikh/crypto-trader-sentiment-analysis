# Crypto Trader Sentiment & Performance Analysis 📊

## Project Overview
This project explores crypto trader transaction behavior and its relationship with market sentiment using the Fear & Greed Index.

The objective was to clean raw trading data, perform exploratory analysis, and extract insights about trader profitability, activity patterns, and risk behavior.

---

## Datasets Used
- **historical_data.csv** → Crypto trade transaction dataset  
- **fear_greed_index.csv** → Market sentiment indicator dataset
- ## Dataset Note

The original `historical_data.csv` file is larger than GitHub's 25MB upload limit.

A smaller sample version (`historical_data_sample.csv`) has been uploaded for reference.
Full Dataset Link:
https://drive.google.com/drive/folders/1Y42eYU2cF-MlqBGKIPiHxDrM9p3s81m0?usp=drive_link


---

## Key Steps Performed

### Data Cleaning & Preprocessing
- Standardized column names
- Converted timestamps into usable date format
- Handled missing values and incorrect datatypes
- Removed invalid numeric records

---

## Exploratory Data Analysis (EDA)

### 1. Daily Profit & Loss Trend
Traders exhibit strong volatility in daily profitability.

### 2. Directional Bias (Buy vs Sell)
Most trades were BUY-side, indicating bullish positioning.

### 3. Top Active Traders
Trading activity is concentrated among a small group of frequent accounts.

### 4. Trade Size vs Profit/Loss
Large trades lead to extreme outcomes, with heavy-tailed distributions.

### 5. Fee Distribution
Fees increase with larger trade volumes and are skewed across traders.

---

## Sentiment Merge Result
The Fear & Greed dataset covers earlier years, while the trading dataset contains trades from later years.

Thus, sentiment-based comparison was limited due to non-overlapping dates.  
Insights were instead derived from trader behavioral metrics such as PnL, volume, and activity patterns.

---

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Google Colab

---

## Conclusion
This analysis provides insights into crypto trader behavior, profitability distribution, and trading concentration patterns.

---

📌 Author: Aman Shaikh  
