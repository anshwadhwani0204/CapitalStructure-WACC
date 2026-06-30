# Capital Structure & WACC Estimation via OLS Regression – FMCG Sector

## Overview

This project estimates the Weighted Average Cost of Capital (WACC) for an FMCG company using a data-driven approach. Instead of relying solely on published estimates, the model derives the cost of equity through CAPM and Ordinary Least Squares (OLS) regression, estimates the cost of debt using a synthetic credit rating methodology, and constructs an optimal capital structure using live market data.

The analysis was implemented in Python with financial data sourced from Yahoo Finance.

---

## Objectives

- Estimate beta using historical market data through OLS regression.
- Calculate cost of equity using the Capital Asset Pricing Model (CAPM).
- Estimate bottom-up beta through peer deleveraging and releveraging.
- Derive pre-tax cost of debt using a synthetic credit rating model.
- Compute the company's Weighted Average Cost of Capital (WACC).
- Analyze the impact of capital structure on valuation.

---

## Methodology

### 1. Data Collection
- Historical stock prices from Yahoo Finance
- Market index returns
- Financial statement data
- Comparable FMCG peer companies

### 2. Beta Estimation
- Top-down beta using OLS regression
- Bottom-up beta using peer deleveraging and releveraging

### 3. Cost of Equity
Using the Capital Asset Pricing Model (CAPM):

> Cost of Equity = Risk-Free Rate + β × Market Risk Premium

### 4. Cost of Debt
Estimated using a synthetic credit rating approach based on:
- Interest Coverage Ratio (ICR)
- Credit spread (CDS)
- Default risk premium

### 5. WACC Estimation

Calculated using market-value weights of debt and equity:

> WACC = (E/V × Re) + (D/V × Rd × (1 − Tax Rate))

---

## Key Results

| Metric | Result |
|---------|--------:|
| OLS Beta | **0.77** |
| Number of Comparable Firms | **5 FMCG Companies** |
| Equity Weight | **98.4%** |
| Interest Coverage Ratio | **18.97** |
| Synthetic Credit Rating | **AAA** |
| Credit Spread (CDS) | **75 bps** |
| Estimated WACC | **13.96% (Top-down)** |
| Estimated WACC | **17.32% (Bottom-up)** |

---

## Technologies Used

- Python
- Jupyter Notebook
- yfinance
- pandas
- numpy
- statsmodels
- matplotlib

---


## Skills Demonstrated

- Financial Modeling
- Corporate Finance
- Capital Structure Analysis
- WACC Estimation
- CAPM
- OLS Regression
- Bottom-up Beta Estimation
- Synthetic Credit Rating
- Financial Data Analysis
- Python for Finance

---

## Key Takeaways

- Estimated equity beta using both statistical and fundamental approaches.
- Constructed a market-based capital structure using live financial data.
- Applied synthetic credit analysis to estimate borrowing costs without relying on external credit ratings.
- Developed a reusable Python workflow for corporate valuation and cost of capital estimation.

---

## Disclaimer

This project was developed for educational and portfolio purposes. Results depend on market conditions, selected assumptions, and the analysis period and should not be interpreted as investment advice.

---

## Author

**Ansh Wadhwani**

BITS Pilani, Hyderabad Campus  
Finance Minor
