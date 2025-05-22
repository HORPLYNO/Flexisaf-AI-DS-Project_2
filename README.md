# Flexisaf-AI-DS-Project_2

Export Data Analysis and Prediction 

This project analyzes export data from multiple products and countries to uncover key drivers of export value and build models to predict future export performance.

Overview
Exploratory Data Analysis (EDA):
We examined the dataset to understand product export frequencies, export values by product and country, and export trends over time.

Correlation Insights:
Analysis revealed that Export Value is strongly influenced by Units Sold and Unit Price, with correlation coefficients of 0.77 and 0.64 respectively.
Profit per Unit showed negligible correlation with these factors, suggesting it depends on other variables not captured in this dataset.

Visualization:
Bar charts and time series plots illustrate top products, leading export countries, and export value fluctuations over time.

Predictive Modeling:
Multiple regression models (Linear Regression, Random Forest, Gradient Boosting) were trained to predict total export value based on features like product, export country, units sold, and unit price.
Models demonstrated strong predictive performance, with Random Forest and Gradient Boosting achieving near-perfect R² scores.

Why It Matters
Insights from this analysis can guide business strategies, optimize product focus, and support forecasting for export revenues. Understanding what drives export success is critical for stakeholders in trade, supply chain, and economic planning.

Dataset
The data is sourced from Kaggle and includes export transactions with features such as product name, export country, units sold, unit price, profit per unit, export value, and date.

Technical Details

Python (Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn) used for data processing, visualization, and modeling.

Correlation analysis quantified linear relationships between variables.

Model evaluation metrics include R², MAE, MSE, and RMSE to assess prediction accuracy.

