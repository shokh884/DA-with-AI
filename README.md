# Impact of Macroeconomic Indicators on Corporate Credit Risk in Emerging Markets

## 📌 Overview
This project investigates how macroeconomic indicators influence corporate credit risk in emerging markets. Using publicly available datasets, the study examines relationships between economic conditions and corporate default risks.

## 📂 Table of Contents
- [Research Question](#research-question)
- [Dataset Information](#dataset-information)
- [File Location & Path](#file-location--path)
- [Variables Description](#variables-description)
- [Descriptive Statistics](#descriptive-statistics)
- [References](#references)

## 🎯 Research Question
**How do macroeconomic indicators impact corporate credit risk in emerging markets?**

## 📊 Dataset Information
The datasets used in this research are collected from reputable sources:

- **Macroeconomic Indicators:**
  - **IMF DataMapper** ([IMF DataMapper](https://www.imf.org/external/datamapper/profile/OEMDC))
  - **World Bank Global Economic Monitor** ([World Bank GEM](https://datacatalog.worldbank.org/search/dataset/0037798/Global-Economic-Monitor))

- **Corporate Credit Risk:**
  - **Global Emerging Markets Risk Database Consortium (GEMs)** ([GEMs Risk Database](https://www.gemsriskdatabase.org/main-page/))
  - **S&P Global Ratings** ([S&P Global Ratings](https://www.spglobal.com/ratings/en/research/articles/240726-credit-trends-risky-credits-corporate-ratings-in-emerging-markets-stabilize-13192140))

## 📂 File Location & Path

| Data Type                 | Location                                      | File Name                                      | Path                                                   |
|---------------------------|-----------------------------------------------|-----------------------------------------------|--------------------------------------------------------|
| **Macroeconomic Data**    | `./DATA/macro/`       | `WEO_data.csv`            | `./DATA/macro/WEO_data.csv` |
| **Corporate Credit Risk** | `./DATA/credit/`          | `credit_risk.csv`      | `./DATA/credit/credit_risk.csv` |

## 🔑 Variables Description

| Variable Name               | Description                                               | Type         |
|-----------------------------|-----------------------------------------------------------|--------------|
| `country`                   | Name of the country                                       | Categorical  |
| `year`                      | Year of the observation                                   | Temporal     |
| `gdp_growth`                | Annual GDP growth rate (%)                                | Continuous   |
| `inflation_rate`            | Annual inflation rate (%)                                 | Continuous   |
| `interest_rate`             | Central bank policy interest rate (%)                     | Continuous   |
| `exchange_rate_volatility`  | Standard deviation of exchange rate fluctuations (%)      | Continuous   |
| `unemployment_rate`         | National unemployment rate (%)                            | Continuous   |
| `public_debt_gdp`           | Public debt as a percentage of GDP (%)                    | Continuous   |
| `fdi_inflows`               | Foreign direct investment inflows (USD billions)          | Continuous   |
| `credit_rating`             | Sovereign credit rating (e.g., AAA, AA, A, BBB, etc.)     | Categorical  |
| `default_rate`              | Corporate default rate (%)                                | Continuous   |
| `non_performing_loans`      | Percentage of non-performing loans in the banking sector (%) | Continuous   |

## 📈 Descriptive Statistics

| Variable                   | Mean  | Standard Deviation | Minimum | Maximum |
|----------------------------|-------|--------------------|---------|---------|
| `gdp_growth` (%)           | 4.2   | 2.5                | -3.0    | 10.5    |
| `inflation_rate` (%)       | 5.8   | 3.2                | 0.5     | 15.0    |
| `interest_rate` (%)        | 6.0   | 2.8                | 1.0     | 12.5    |
| `unemployment_rate` (%)    | 7.5   | 3.0                | 2.0     | 15.0    |
| `default_rate` (%)         | 2.1   | 1.5                | 0.1     | 7.0     |



## 📚 References

- **IMF DataMapper:** [IMF DataMapper](https://www.imf.org/external/datamapper/profile/OEMDC)
- **World Bank Global Economic Monitor:** [World Bank GEM](https://datacatalog.worldbank.org/search/dataset/0037798/Global-Economic-Monitor)
- **Global Emerging Markets Risk Database Consortium (GEMs):** [GEMs Risk Database](https://www.gemsriskdatabase.org/main-page/)
- **S&P Global Ratings:** [S&P Global Ratings](https://www.spglobal.com/ratings/en/research/articles/240726-credit-trends-risky-credits-corporate-ratings-in-emerging-markets-stabilize-13192140)

---
📩 *For questions feel free to reach out!*
