# Dynamic Interplay: Alpha Generation through VAR and PCA Integration
## Using VAR (Vector autoregression) time series model and PCA (Principal Component Analysis) machine learning model to create an optimized portfolio.
## Project for STAT5261 - Statistical Methods in Finance (Columbia University)

### Procedure
1. Selection of stocks: We need to select individual stocks (5-10) to understand the dynamic relationships between them. VAR models with many individual stocks in a large portfolio can become complex and computationally intensive therefore limiting to 10.
2. Timeseries modelling: We will apply VAR(p) model with an appropriate lag p to forecast returns of these given stocks. To optimize p we will use AIC, BIC, HQ We can also use ACF plots, stationarity tests, RMSE values and Confidence intervals.
3. Portfolio allocation: -
4. Efficiency and risk measures: Calculation of absolute returns and RAR (Sharpe's/Sortino's ratio), VaR, ES, hypothesis testing (t-test null: no significant difference in the mean returns), regression analysis (alpha - active return, beta - market sensitivity), and other interesting measures (After how many days does your variance cross 50%? On how many days in a given time T, does the portfolio lose it's value by 50%? etc.)
5. Model comaprisons: (a) Market index as benchmark. (b) An equally weighted unoptimized portfolio.
