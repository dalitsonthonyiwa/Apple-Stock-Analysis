# 🍎 Apple (AAPL) Hourly Stock Data Analysis 📊

This project analyzes **Apple Inc. (AAPL) hourly stock prices** using financial time series techniques.  
It focuses on **returns analysis, autocorrelation diagnostics, and volatility modeling** using ARCH/GARCH models — common tools in quantitative finance and financial engineering.

---

## 🚀 Project Overview

- **Data Source:** Alpha Vantage API
- **Ticker:** AAPL
- **Interval:** 1-hour (intraday)
- **Output Size:** Full historical dataset

### Analysis Scope
- Fetching intraday stock price data via API
- Data cleaning and preprocessing
- Returns calculation
- Autocorrelation & partial autocorrelation analysis (ACF & PACF)
- Volatility modeling using ARCH/GARCH

---

## 🛠️ Tools & Libraries

- **Python 3**
- **pandas** – Data handling and preprocessing
- **matplotlib** – Visualization
- **statsmodels** – ACF & PACF analysis
- **arch** – ARCH/GARCH volatility modeling
- **requests** – API calls to Alpha Vantage

---

## 📈 Methodology

### 1️⃣ Data Collection
- Fetch intraday AAPL price data from the **Alpha Vantage API**
- Store and structure data using pandas

### 2️⃣ Data Preparation
- Timestamp parsing
- Sorting and indexing time series
- Handling missing values

### 3️⃣ Returns Calculation
- Compute log returns from hourly closing prices
- Visualize return behavior over time

### 4️⃣ Autocorrelation Analysis
- Plot **ACF (Autocorrelation Function)**
- Plot **PACF (Partial Autocorrelation Function)**
- Identify serial dependence in returns

### 5️⃣ Volatility Modeling
- Apply **ARCH/GARCH models**
- Capture **time-varying volatility**
- Analyze volatility clustering in returns

---

## 📊 Key Insights

- 📉 Stock returns exhibit **volatility clustering**
- 📈 Volatility is **time-dependent**, not constant
- 🔍 GARCH models effectively capture changing market risk
- 🧠 Demonstrates practical **financial engineering & time series modeling skills**

---

## 📌 Example Visualizations

- Hourly price series
- Return series
- ACF & PACF plots
- Conditional volatility from GARCH model

---

## 🔑 API Notes

- Requires a **free Alpha Vantage API key**
- Set your API key as an environment variable:

```bash
export ALPHAVANTAGE_API_KEY="your_api_key_here"

