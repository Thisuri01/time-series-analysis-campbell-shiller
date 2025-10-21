# Univariate and Multivariate Time Series Modelling of S&P 500 Returns, Dividend Growth, and VAR Dynamics using Campbell-Shiller Data

## Executive Summary
This study analyzes the S&P 500 returns, dividend growth, and their dynamic relationships using the Campbell-Shiller dataset, which provides comprehensive long-term data on stock prices, dividends, and earnings. The dataset spans a monthly frequency from June 1871 to December 2017, offering a rich historical framework for analysis. Using EViews software, advanced econometric techniques including ARMA, EGARCH, and VAR models were applied to uncover the underlying time series properties, volatility patterns, and interdependencies within these financial variables. The analysis provides valuable insights into market efficiency, volatility clustering, leverage effects, and the predictive role of dividend growth in stock returns, contributing to a deeper understanding of stock market dynamics over an extended historical horizon.

## Business Problem
Estimating the behavior and interrelations of stock returns and dividends is crucial for investors and policymakers. The Campbell-Shiller data enables a comprehensive understanding of how valuation ratios and dividend growth influence market dynamics over time, addressing challenges related to forecasting returns and managing investment risks effectively.

## Methodology
- Stationarity tests (Augmented Dickey-Fuller) were performed on returns, dividends, and prices from the Campbell-Shiller dataset.
- ARMA models characterized the conditional mean behavior of returns and dividend growth.
- EGARCH models captured volatility clustering and asymmetric effects in the data.
- VAR models explored causal relationships between returns and dividend growth, incorporating up to 12 lags to capture short-run dynamics.
- Various diagnostic tests validated model adequacy and performance.

## Skills
- Time series econometrics with real-world financial data
- Handling and analyzing Campbell-Shiller historical market data
- ARMA and GARCH family volatility modeling
- Vector autoregression in financial contexts
- Statistical testing and model diagnostics
- Data-driven financial research and forecasting

## Results and Recommendations

### S&P 500 Returns
<img width="702" height="435" alt="Screenshot 2025-10-21 093738" src="https://github.com/user-attachments/assets/6dbd7c4d-8d8d-40ac-896e-148d02832e4b" />

### Dividend Growth Rate
<img width="703" height="438" alt="Screenshot 2025-10-21 093817" src="https://github.com/user-attachments/assets/1f60791f-9fa1-44c9-b97a-6aaf056b4f72" />

- S&P 500 returns and dividend growth exhibit distinct statistical properties, including stationarity after appropriate transformations.
- Volatility models reveal persistent and asymmetric volatility, supporting the use of EGARCH for accurate risk modeling.
- Dividend growth is highly persistent, showing momentum effects influencing returns.
- VAR results indicate bidirectional causality with complex interdependencies.
- The Campbell-Shiller data confirms traditional valuation metrics remain useful predictors of long-term market behavior.
- Investors should incorporate volatility dynamics and dividend signals in their asset allocation strategies.

## Next Steps
- Supplement Campbell-Shiller data with macroeconomic indicators to enrich model explanatory power.
- Expand analysis to higher-frequency data for finer volatility assessment.
- Deploy model insights to develop enhanced forecasting and risk management tools.
- Explore machine learning integrations for predictive improvements.


