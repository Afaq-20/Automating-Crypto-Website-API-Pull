# 📊 Automating Crypto Website API Pull

A Python project that automates cryptocurrency data extraction from the CoinMarketCap API, stores it in a CSV file, and performs time-based and percentage-change analysis using Pandas and Seaborn.

---

## 🚀 Project Overview

This project demonstrates how to:

- Connect to a live cryptocurrency API
- Extract real-time market data
- Automate data collection at fixed intervals
- Store structured data into a CSV file
- Perform transformation and analysis using Pandas
- Visualize market trends using Seaborn & Matplotlib

The script continuously pulls data and builds a growing dataset for analysis.

---

## 🛠 Technologies Used

- Python
- Requests (API calls)
- Pandas (Data cleaning & transformation)
- Seaborn & Matplotlib (Data visualization)
- CoinMarketCap API

---

## 📌 Key Features

### 1️⃣ API Integration
- Connects to CoinMarketCap Pro API
- Pulls top 15 cryptocurrencies
- Converts values to USD
- Handles connection errors gracefully

### 2️⃣ Data Automation
- Runs automatically every 60 seconds
- Appends new data to a CSV file
- Adds timestamps for tracking price changes over time

### 3️⃣ Data Transformation
- JSON normalization into structured DataFrame
- Grouping and reshaping using:
  - `groupby()`
  - `stack()`
  - `reset_index()`
- Cleaning column names for better readability

### 4️⃣ Percentage Change Analysis
Tracks:
- 1 hour change
- 24 hour change
- 7 day change
- 30 day change
- 60 day change
- 90 day change

### 5️⃣ Data Visualization
- Point plots for multi-coin comparison
- Line charts for time-series analysis (e.g., Bitcoin price tracking)

---

## 📈 Example Analysis

- Compared percent changes across multiple time horizons.
- Visualized Bitcoin price movement over time using timestamped data.
- Identified short-term vs long-term volatility patterns.

---

## 🎯 Purpose of the Project

This project showcases:

- API handling skills
- Automation and scheduling logic
- Real-world data engineering workflow
- Data cleaning and reshaping techniques
- Time-series analysis fundamentals
- Data visualization capabilities

---

## 📁 How It Works

1. Connect to API
2. Fetch latest crypto listings
3. Normalize JSON response
4. Append results to CSV
5. Repeat every 60 seconds
6. Perform analysis on stored dataset

---

## ⚠ Important Note

For security reasons:
- Never expose your API key publicly.
- Store API keys using environment variables in production.

---

## 📌 Author

Built as part of a data analytics portfolio to demonstrate API automation, data transformation, and market trend analysis skills.
