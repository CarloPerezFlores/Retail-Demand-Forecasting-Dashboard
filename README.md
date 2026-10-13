# Retail Demand Forecasting & Commercial Analytics

## Project Overview

This project analyzes historical retail sales data, compares machine learning models for demand forecasting, and presents commercial insights through an interactive Power BI dashboard.

The objective is to support data-driven decisions in demand planning, sales analysis, and promotional planning.

## Business Objectives

- Analyze historical sales trends across stores, cities, states, and product families.
- Compare predictive models to identify the best-performing forecasting approach.
- Evaluate actual sales against model predictions during the validation period.
- Visualize sales, forecast performance, and promotional activity in Power BI.
- Translate analytical results into actionable commercial insights.

## Methodology

1. **Data Understanding:** Explore the available sales data and identify relevant variables.
2. **Data Preparation:** Prepare datasets for analysis and modeling.
3. **Model Development:** Compare Baseline, Linear Regression, Random Forest, and XGBoost.
4. **Model Evaluation:** Evaluate predictions using R², Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).
5. **Business Intelligence:** Build a Power BI dashboard covering executive overview, demand forecasting, and commercial planning.

## Model Results

XGBoost achieved the strongest performance among the evaluated models.

| Metric | XGBoost Result |
|---|---:|
| R² | 0.9616 |
| MAE | 69.94 |
| RMSE | 266.95 |

These results reflect performance on the validation data. MAE and RMSE are expressed in the target variable's units.

## Power BI Dashboard

The dashboard contains three pages:

- **Executive Overview:** Historical sales, geographic analysis, product-family performance, store clusters, and model comparison.
- **Demand Forecast:** Actual sales versus predictions, model metrics, and daily forecast errors.
- **Commercial Planning:** Monthly sales and promotional activity trends.

## Tools & Technologies

- Python
- Pandas
- Scikit-learn
- XGBoost
- Jupyter Notebook
- Power BI
- Git and GitHub

## Business Value

The analysis demonstrates how historical data, predictive modeling, and business intelligence can support demand planning and commercial decision-making.

The promotional analysis identifies trends for further investigation; it does not establish that promotions directly cause sales increases.

## Project Status

The analytical notebook, model evaluation, and Power BI dashboard have been developed. Repository documentation and publication are in progress.