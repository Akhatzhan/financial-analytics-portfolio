# Financial Analytics Portfolio

## Project 1: Apple (AAPL) Financial Analysis (2009–2023)

### Problem
Analyze Apple's financial performance over 14 years to identify growth trends, anomalies, and profitability patterns.

### Data
- Source: Financial Statements of Major Companies (Kaggle)
- 161 rows, 23 columns
- Companies: AAPL, MSFT, GOOG, NVDA, AMZN and others

### Approach
- Loaded and explored data using Python (pandas)
- Built 4 visualizations using matplotlib

### Key Findings
- Revenue grew consistently from ~$40B (2009) to ~$390B (2023)
- Notable slowdown in 2015–2016 followed by sharp growth post-2020
- Net Profit Margin stayed stable at 20–25% across most years
- ROE increased dramatically after 2019, indicating stronger returns for shareholders

### Tools
Python, pandas, matplotlib, Kaggle Notebook

### Files
- `notebook97da2314e3.ipynb` — full analysis notebook

## Project 2: Investment Portfolio Analysis (2019–2024)

### Problem
Analyze and compare performance of 6 major stocks to identify best risk/return profiles.

### Data
- Source: Yahoo Finance via yfinance API
- 6 stocks: AAPL, MSFT, GOOG, NVDA, AMZN, JNJ
- Daily prices 2019–2024 (1258 rows)

### Approach
- Calculated total return, annual volatility, correlations
- Built 4 Python visualizations
- Built interactive Power BI dashboard with slicer

### Key Findings
- NVDA returned +1365% — highest by far
- JNJ lowest volatility (19.8%) — best defensive option
- AAPL and MSFT highly correlated (0.76)
- NVDA highest risk (51.7%) but justified by returns

### Tools
Python, pandas, matplotlib, seaborn, yfinance, Power BI Desktop

### Files
- `notebookca0e7e5503.ipynb` — Python analysis
- `investment_portfolio_dashboard.pbix` — Power BI dashboard
- `Снимок экрана 2026-07-09 131800.png` — dashboard screenshot
