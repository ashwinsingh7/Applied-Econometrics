# Applied Econometrics: Modelling the Stock Market in 2020 Using Macroeconomic Variables and Covid-19 Events


## Project Overview

This project investigates the impact of economic variables and the COVID-19 pandemic on the stock market, specifically the S&P 500 index. Using econometric modeling, multiple regression models were developed to analyse the relationships between mobility, oil prices, government interventions, and financial indicators during the pandemic. The study uses theoretically-grounded explanatory variables and rigorous statistical testing to refine the model and accuracy.


## Objective

To formulate an econometric model that explains variations in the S&P 500 index based on economic indicators and pandemic-related factors, providing insights into market behavior during crises.


## Data Sources

Mobility data: IHME (Institute for Health Metrics and Evaluation)

Stock market data: Yahoo Finance

Oil Prices: West Texas Intermediate (WTI) and Brent Crude (FRED Economic Data)

Gold Prices: London Bullion Market

Bond Yields: U.S. 10-Year Sovereign Bonds


## Methodology

Model Development: Four econometric models were built, each refining the selection of variables based on statistical significance and diagnostic tests.

Variable Selection: Factors such as mobility changes, oil prices, gold prices, and bond yields were considered due to their theoretical link to stock market movements.

Regression Analysis: Ordinary Least Squares (OLS) regression was used to estimate the impact of each variable on the S&P 500 index.

Multicollinearity: Variance Inflation Factor (VIF) was used to detect and eliminate highly correlated regressors.

Autocorrelation: Breusch-Godfrey test identified serial correlation, corrected using HAC standard errors.

Misspecification Errors: Ramsey’s RESET test used to investigate model misspecification.

Normality: Jarque-Bera test assessed residual distribution.

<img width="300" alt="Model IV (residuals vs time)" src="https://github.com/user-attachments/assets/bf98d63a-492b-491f-9aca-fda0be3ab43e" />  <img width="300" alt="Model IV residual hist plot" src="https://github.com/user-attachments/assets/d4df1ec9-e65b-4fa9-926d-d650506319a8" />




## Key Findings

Mobility and Stock Market Movements: Increased mobility correlated positively with stock market growth, indicating higher economic activity and positive investor sentiment.

Impact of Oil Prices: Initially, WTI crude was included but found insignificant. Brent Crude was a better predictor of stock market changes.

Effect of Gold Prices: Contrary to expectations, gold prices showed a weak positive correlation with the stock market, likely due to investor shifts to bonds and cash holdings instead.

Pandemic Announcements: Government interventions and major pandemic-related news negatively impacted the S&P 500 index.

Sovereign Bond Yields: Increased bond yields positively correlated with stock market movements, aligning with investor expectations of risk-return trade-offs.

<img width="651" alt="Model IV regression" src="https://github.com/user-attachments/assets/8bf54ad8-027a-4736-9a80-84b6654701cd" />
<img width="651" alt="Screenshot 2025-03-24 at 11 08 52 AM" src="https://github.com/user-attachments/assets/10fbd098-437a-4530-bc7f-0c2528ad274d" />


## Final Model

The final regression model includes:

- Mobility Change
- Brent Crude Oil Prices
- Pandemic-Related Events (Dummy Variable)
- Gold Prices
- 10-Year Sovereign Bond Yields

This model explains 93% of the variation in the S&P 500 index with all variables statistically significant at the 1% level.

<img width="600" alt="Model IV Plot" src="https://github.com/user-attachments/assets/317d1ba7-662e-4403-b5ef-045d4ebb5b8e" />

