# Stock_Market_Analysis

## 📌 Project Overview
An end-to-end SQL-based analysis of stock market trends using historical data from Yahoo Finance. This project demonstrates advanced analytical techniques including **window functions**, **moving averages**, and **volatility modeling** to extract actionable market insights.

## 🛠️ Tech Stack
* **Database:** PostgreSQL / MySQL (Select yours)
* **Data Source:** Yahoo Finance API / Kaggle
* **Key Functions:** LEAD, LAG, AVG() OVER(), PARTITION BY

## 🚀 Key Analysis Features

### 1. Time-Series Volatility & Momentum
Engineered queries to calculate daily price volatility (High-Low spread) and momentum shifts using `LAG` functions to compare current closing prices with previous sessions.

### 2. Technical Indicators (Moving Averages)
Developed **7-day** and **30-day Rolling Averages** to filter out daily market noise. This helps identify long-term bullish and bearish trends via a "Trend Signal" logic.

### 3. Sector Performance Benchmarking
Utilized `PARTITION BY` clauses to compare individual ticker performance against broader sector averages, identifying stocks that are outperforming their industry peers.
