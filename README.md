mpact of Trade Factors on GDP Growth | OLS Regression Analysis

This project investigates the relationship between international trade factors and GDP growth using Ordinary Least Squares (OLS) regression. Through rigorous diagnostic testing and iterative model refining, the study isolates the primary trade drivers impacting GDP performance.

Key Findings
* Tariffs Suppress Growth: The final model reveals a statistically significant negative relationship between Customs Duties (as a % of GDP) and overall GDP Growth.

* Parsimony Wins: Simplifying the model by dropping collinear, non-significant variables (TRADE OPENNESS/GDP and NET EXPORTS/GDP) significantly improved structural reliability without losing explanatory power.

Analytical Strategy & Diagnostics
* Multicollinearity Resolution: Initial multi-variable specs suffered from high Variance Inflation Factor (VIF) scores, making it impossible to isolate individual effects. Removing redundant predictors eliminated multicollinearity.

* Model Validation: The final single-predictor model (CUSTOM/GDP) satisfies key OLS assumptions, passing normality checks (Omnibus Prob = 0.551) with an acceptable independence profile (Durbin-Watson = 1.492).

Tech Stack & Methods
Python • Pandas • Statsmodels • OLS Regression • VIF Analysis • Hypothesis Testing
