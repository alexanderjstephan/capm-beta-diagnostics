# CAPM Beta Estimation and Regression Diagnostics

## Overview
This project estimates CAPM betas for AAPL, TSLA, and JPM and performs regression diagnostics (linearity, independence, homoscedasticity, normality). The project incorporates linear regression and percent return calculations to estimate the value of beta and employs residual plots, the Durbin-Watson test, Breusch-Pagan test, and QQ plots to validate the regression.

## Motivation
Understanding systemic risk is essential for portfolio creation. This project demonstrates how to estimate and interpret CAPM beta using real market data from Q2 2024 to Q1 2025.

## Data
- Source: Yahoo Finance (AAPL, JPM, TSLA, ^GSPC)
- Period: March 2024 to March 2025

## Results
- **AAPL beta:** 0.96
- **TSLA beta:** 2.81
- **JPM beta:** 0.92

## How to Run
1. Clone this repo
2. Install dependencies: `pip install -r requirements.txt`
3. Open `notebook.ipynb` in Jupyter and run all cells

## Discussion
- Interpretation of betas and diagnostics
- Limitations (e.g., short time frame, outliers)
- Possible extensions (e.g., Fama-French model)

## License
MIT License

## Credits
- **Data:** Yahoo Finance
- **Libraries:** pandas, yfinance, numpy, matplotlib, seaborn, scipy, jupyter
- **Background Reading:**
  - Capital Asset Pricing Model (CAPM): Definition, Formula, and Assumptions, Investopedia
  - Regression diagnostics:  testing the assumptions of linear regression, Duke University
  - The Breusch-Pagan Test: Definition & Example, Statology
  - Understanding QQ Plots, UVA Library
  - Durbin Watson Statistic, Corporate Finance Institute
- **Author:** Alexander Stephan

## Last Updated
July 2, 2025

