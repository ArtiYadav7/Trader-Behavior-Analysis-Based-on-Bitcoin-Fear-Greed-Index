# Trader Behavior vs Bitcoin Market Sentiment Analysis

## Project Overview

This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader performance using historical trading data from Hyperliquid.

The objective is to identify how market emotions influence trading behavior, profitability, leverage usage, and overall trader performance.

---

## Problem Statement

Crypto markets are highly sentiment-driven. Traders often react emotionally during periods of fear and greed, which can significantly affect profitability and risk-taking behavior.

This project aims to uncover:
- Whether traders perform better during Fear or Greed markets
- How leverage changes across market sentiment
- Win/loss behavior under different emotions
- Trading activity patterns
- Behavioral insights from trader data

---

## Datasets Used

### 1. Bitcoin Fear & Greed Index Dataset
Contains:
- Date
- Market Sentiment Classification
  - Fear
  - Extreme Fear
  - Greed
  - Extreme Greed

### 2. Historical Trader Data (Hyperliquid)
Contains:
- Account
- Coin
- Execution Price
- Size Tokens
- Size USD
- Side
- Timestamp
- Closed PnL
- Fee
- Direction
- etc.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook

---

## Project Workflow

### 1. Data Cleaning
- Handled date conversion
- Removed duplicates
- Checked missing values

### 2. Data Merging
Merged trader data with sentiment data using common date fields.

### 3. Feature Engineering
Created:
- Profit/Loss flag
- Trade volume
- Absolute PnL
- Trade hour

### 4. Exploratory Data Analysis (EDA)
Performed:
- Sentiment distribution analysis
- PnL analysis
- Win rate analysis
- Buy vs Sell analysis
- Hourly trading analysis
- Correlation analysis
- Top trader analysis

### 5. Statistical Testing
Applied T-Test to evaluate significance between Fear and Greed profitability.

---

## Key Insights

- Trader profitability varies significantly across market sentiment.
- Fear periods show increased volatility and inconsistent performance.
- Greed periods often exhibit higher trading activity.
- Certain traders maintain profitability regardless of market conditions.
- Trade size does not always correlate with profitability.

---

## Visualizations Included

- Countplots
- Boxplots
- Scatterplots
- Bar Charts
- Correlation Heatmap
- Hourly Trend Analysis

---

## Files Included

```text
PimeTradePro.ipynb
fear_greed_index.csv
historical_data.csv
README.md
requirements.txt
