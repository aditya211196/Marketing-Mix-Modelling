# Marketing-Mix-Modelling

Marketing Mix Modeling for FMCG Sales Optimization
Problem Statement
An FMCG brand ("Brand X") was sold across 4,000+ retail stores with varying pricing, promotional strategies, and product availability. The objective of this project was to quantify how key marketing levers—price, in-store promotions, product variants, and competitor pricing—influence sales performance. The goal was to develop a model that could help optimize marketing strategies and improve revenue forecasting.

Approach
Data Understanding & Preparation

Variables included:

Price: Average price of Brand X per store

Feature: Availability of value-added variants (proxy for product)

Display: In-store promotion presence (proxy for promotion)

Price_Competitor1 to Price_Competitor5: Prices of competing brands

Sales: Target variable (units sold or revenue per store)

Cleaned and structured data for regression analysis.

Model Building

Used stepwise linear regression in Python to iteratively add variables and test their contribution to model accuracy.

Introduced interaction terms (e.g., Price × Promotion) to capture combined effects.

Evaluated model using:

Adjusted R²: To measure explanatory power

Mean Absolute Error (MAE): To assess prediction accuracy

Applied 95% confidence level tests to determine significance of predictors.

Interpretation

Analyzed model coefficients, p-values, and residuals to validate findings.

Identified statistically significant variables contributing to sales variance.

Key Findings
Price had a strong inverse relationship with sales, indicating price sensitivity.

In-store promotions significantly boosted sales, especially at mid-range price points.

Only 2 out of 5 competitor prices had a meaningful impact on Brand X’s sales.

Availability of value-added variants had a positive but relatively smaller influence.

Recommendations
Focus promotional efforts at optimal price bands to maximize ROI.

Monitor key competitors only (those with statistically significant influence).

Improve distribution of value-added variants in targeted regions where they enhance performance.

Use the model for scenario analysis and to guide pricing and promotional strategy.

Tools & Technologies
Python

pandas, statsmodels

Linear regression, interaction effects

Statistical significance testing
