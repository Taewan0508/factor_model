# Fama–French 3-Factor Model

This project performs a full Fama–French 3-Factor regression analysis on major U.S. tech stocks (TSLA, NVDA, AAPL) to understand how much of their returns are explained by market, size, and value risk factors.
It includes:

1. Data downloading (stocks + Fama–French factors)
2.Daily return calculation
3.Excess return computation
4.OLS regression for each stock
5.Extraction of betas, t-stats, R²
6.Visualization of exposures and statistical significance

##🧠 What This Project Shows
This project answers key quantitative finance questions:
✔ How exposed are TSLA, NVDA, and AAPL to the market factor?
(Their market beta)

✔ Do these stocks behave like small-cap or large-cap firms?
(SMB exposure)

✔ Are these stocks value stocks or growth stocks?
(HML exposure)

✔ How much of each stock’s return is explained by the 3-Factor Model?
(R² values)

✔ Which factor exposures are statistically significant?
(t-stat analysis)

##📦 Features

Daily stock price retrieval via yfinance
Automatic fetching of Fama–French factors via pandas_datareader
Robust handling of missing factor data
Clean date alignment between return series and factor series
Regression via statsmodels.OLS
Beta + t-stat plotting with matplotlib & seaborn


##📊 Output Examples
1. Factor Betas
Shows exposure to:
Market (Mkt-RF)
Size (SMB)
Value (HML)

2. t-Statistics
Shows statistical significance:
|t| > 2 → significant factor

3. R² Values
Explains how much variance the model captures.

