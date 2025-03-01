# Impact of Macroeconomic Indicators on Corporate Credit Risk in Emerging Markets

## 📌 Overview
This research investigates how macroeconomic indicators influence corporate credit risk in emerging markets. Using historical economic and financial data, the study aims to identify key factors affecting corporate credit ratings and default probabilities.

## 📂 Table of Contents
- [Introduction](#introduction)
- [Research Question](#research-question)
- [Dataset Information](#dataset-information)
- [File Location & Path](#file-location--path)
- [Variables Description](#variables-description)
- [Descriptive Statistics](#descriptive-statistics)
- [References](#references)

## 📖 Introduction
Corporate credit risk is significantly impacted by macroeconomic conditions, particularly in emerging markets where economic volatility is higher. Understanding these relationships can improve credit risk prediction models and inform policy decisions.

## 🎯 Research Question
**How do macroeconomic indicators impact corporate credit risk in emerging markets?**

## 📊 Dataset Information
- **Source:** World Bank, IMF, S&P, Moody’s, Fitch Ratings, Bloomberg
- **Time Period:** 2000 - 2024
- **Countries:** Selected emerging markets (Brazil, India, Indonesia, Mexico, South Africa, Turkey, etc.)
- **Observations:** ~50,000 corporate-level data points

## 📂 File Location & Path
- **Location:** `./datasets/corporate_credit_risk/`
- **File Format:** CSV
- **Path:** `./datasets/corporate_credit_risk/emerging_markets_credit_risk.csv`

## 🔑 Variables Description

| Variable Name               | Description                                               | Type    |
|-----------------------------|-----------------------------------------------------------|---------|
| `credit_rating`             | Corporate credit rating (AAA, AA, A, BBB, etc.)         | Categorical |
| `default_probability`       | Probability of default (0-1 scale)                      | Continuous |
| `gdp_growth`               | Annual GDP growth rate (%)                              | Continuous |
| `inflation_rate`           | Annual inflation rate (%)                               | Continuous |
| `interest_rate`            | Central bank interest rate (%)                         | Continuous |
| `exchange_rate_volatility` | Standard deviation of exchange rate changes (%)        | Continuous |
| `unemployment_rate`        | National unemployment rate (%)                         | Continuous |
| `public_debt_gdp`         | Public debt as % of GDP                                | Continuous |
| `fdi_inflows`             | Foreign direct investment inflows (in billion USD)     | Continuous |
| `corporate_leverage`       | Corporate debt-to-equity ratio                         | Continuous |
| `non_performing_loans`     | Percentage of non-performing loans in banking sector   | Continuous |
| `stock_market_volatility`  | Volatility of major stock index (%)                    | Continuous |
| `export_growth`            | Annual export growth (%)                               | Continuous |
| `commodity_price_index`    | Index of major export commodities                      | Continuous |
| `bankruptcy_rate`          | Corporate bankruptcy rate (%)                          | Continuous |

## 📈 Descriptive Statistics
Below is a summary of five key variables with their descriptive statistics:

| Variable                 | Mean  | Std Dev | Min  | Max  |
|--------------------------|-------|---------|------|------|
| `default_probability`    | 0.12  | 0.08    | 0.01 | 0.45 |
| `gdp_growth`             | 3.8   | 2.1     | -2.5 | 9.6  |
| `inflation_rate`         | 6.2   | 3.4     | 1.2  | 15.8 |
| `interest_rate`          | 5.4   | 2.7     | 0.5  | 12.0 |
| `corporate_leverage`     | 2.3   | 1.1     | 0.5  | 5.8  |

## 📚 References
- IMF, World Economic Outlook Database
- World Bank, Global Financial Development Report
- S&P, Moody’s, Fitch Ratings Data
- Bloomberg Financial Market Data

---  
📩 For questions or collaboration, feel free to reach out!
