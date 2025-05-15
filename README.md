Econometrics Project: Sales Forecasting with Multiple Regression Models

This project applies econometric modeling techniques to a business dataset that includes daily sales, advertising budget, and seasonal index values. The objective is to determine the effect of advertising and seasonality on sales, and to identify the best-fitting model through regression diagnostics and statistical testing.

Dataset
- Shape: 730 rows × 4 columns (daily data)
- Variables:
  - Sales (dependent variable)
  - Advertising budget
  - Seasonal index
  - Date

Models Used
1. Linear-Linear Model  
2. Log-Log Model  
3. Log-Linear Model

Summary of Findings
- Best Model: Log-log model (based on AIC/BIC and specification tests)
- R²: ~0.726
- All models passed key statistical tests:**
  - T-Test & F-Test: Significant coefficients and overall model
  - VIF Test: No multicollinearity
  - ADF Test: Data is stationary
  - MWD Test: Model correctly specified
  - Chow Test: No structural break
  - Park, Goldfeld Tests: Homoscedasticity confirmed
  - Durbin-Watson: No autocorrelation

Tools & Libraries
- Python (Jupyter Notebook)
- pandas, statsmodels, matplotlib
- econometric test functions (custom / statsmodels)

Key Skills Applied
- Model comparison using R², AIC, BIC
- Residual analysis & specification tests
- Econometric hypothesis testing (ADF, Chow, Wald, etc.)
