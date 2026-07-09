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

## Project 3: Customer Segmentation — RFM Analysis

### Problem
Segment 4,338 customers of a UK retail company to identify high-value and at-risk groups.

### Data
- Source: Online Retail Dataset (Kaggle, UCI)
- 541,909 transactions → 397,884 after cleaning
- Period: 2010–2011, UK-based retailer

### Approach
- Cleaned data: removed nulls, negative quantities, zero prices
- Calculated RFM metrics per customer (Recency, Frequency, Monetary)
- Scored and segmented into 4 groups: Champions, Loyal, Recent, At Risk
- Built 4 visualizations

### Key Findings
- Champions (1,523 customers) generate avg £4,300 revenue — 10x more than At Risk
- At Risk segment (1,504 customers) hasn't purchased in avg 185 days
- Champions buy avg 8.6x vs At Risk 1.3x — frequency is the key differentiator
- Priority action: retention campaign for At Risk, upsell for Loyal Customers

### Tools
Python, pandas, matplotlib, seaborn, Kaggle Notebook

### Files
- `notebook79aa1990c4.ipynb` — full RFM analysis

## Project 4: Accounts Receivable (AR) Analysis — Based on OneVision Experience

### Problem
Analyze outstanding debts across 100 companies to identify collection risks and prioritize follow-ups.

### Background
Based on real-world experience as Financial Analyst at OneVision (Kazakhstan), where tracking payments across hundreds of companies was a core responsibility.

### Approach
- Generated realistic AR dataset (100 companies, 5 industries)
- Calculated Outstanding Balance, Collection Rate per company
- Aging Analysis: grouped debts by 0-30, 31-60, 61-90, 90+ days
- Identified Top 10 highest-risk debtors

### Key Findings
- 60 out of 100 companies in 90+ days bucket — $2.5M at risk
- Manufacturing has lowest collection rate (43%) — highest priority for follow-up
- Finance sector leads collection rate (59%) — most reliable payers
- Top debtor (Company_49): $138,492 outstanding, 104 days overdue

### Tools
Python, pandas, matplotlib, Kaggle Notebook

### Files
- `notebookf49e8e62de.ipynb` — full AR analysis
