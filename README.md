# Project Title

Demand Forecasting Optimization for Corporation Favorita: A Time Series Regression ML Approach

![Time series Forecast](<images/0JX3-0nZ6nWACUM6E.png>)

## Project Overview

This project aims to optimize inventory management for Corporation Favorita, a large grocery retailer in Ecuador. By developing machine learning models to forecast product demand across various stores, the project seeks to ensure the right quantity of products is always in stock. The key questions address the impact of various factors on sales, including promotions, holidays, and external events. The outcomes include predictive models that aid in inventory decisions, enhancing customer satisfaction and minimizing costs.

## Business Understanding

Corporation Favorita, a large grocery retailer based in Ecuador, aims to optimize its inventory management to ensure the right quantity of products is always in stock across its various locations. Effective inventory management is critical for maintaining high levels of customer satisfaction and minimizing costs associated with overstocking or stockouts.

To achieve this goal, we will build machine learning models to forecast the demand for products at different Favorita stores. Accurate demand forecasting will allow Corporation Favorita to make informed decisions regarding stock levels, promotions, and supply chain logistics.

### Objectives

1. **Develop Predictive Models**: Create models to forecast daily unit sales for thousands of products across multiple stores.
2. **Understand Influencing Factors**: Analyze the impact of various factors on sales, including promotions, holidays, oil prices, store characteristics, and external events such as earthquakes.
3. **Optimize Inventory Management**: Use the models to inform inventory decisions, ensuring that the right products are available at the right stores at the right time.

### Hypotheses

1. Null Hypothesis (H0): Promotions do not have a significant impact on sales.
2. Alternative Hypothesis (H1): Promotions have a significant impact on sales.

## Power BI Dashboard

[Power BI LIVE! Link](https://app.powerbi.com/view?r=eyJrIjoiYmEzYzg3YjctMmVkMS00NzE5LTkxYjMtODEzMWMwOGI3ODEyIiwidCI6IjQ0ODdiNTJmLWYxMTgtNDgzMC1iNDlkLTNjMjk4Y2I3MTA3NSJ9)

![Power BI Dashboard](<images/Screenshot 2024-08-08 113957.png>)

## Data Collection

- Azubi Africa's SQL Server database, GitHub repository and OneDrive.

### Data Sources

- **train.csv**: Time series data of store, product information, promotions, and sales.
- **test.csv**: Features similar to the training data for the 15 days following the last date in the training data.
- **transaction.csv**: Daily transactions per store.
- **stores.csv**: Metadata about stores including location and type.
- **oil.csv**: Daily oil prices.
- **holidays_events.csv**: Information about holidays and events, including special designations like transferred, bridge, and workdays.
- **sample_submission.csv**: A sample submission file for formatting predictions.


## Exploratory Data Analysis (EDA)

Describe the techniques used for exploring the data, including visualizations, statistical summaries, and any initial findings.

## Analytical Questions

**Questions:**

- Is the train dataset complete (has all the required dates)?
- Which dates have the lowest and highest sales for each year?
- Did the earthquake impact sales?
- Are certain groups of stores making more sales than others? (Cluster, city, state, type)
- Are sales affected by promotions, oil prices and holidays?
- What analysis can we get from the date and its extractable features?
- What is the difference between RMSLE, RMSE, MSE (or why is the MAE greater than all of them?)
- What is the total sales made each year by the corporation?

**Visualization Tools:**

- Matplotlib
- Seaborn

## Modeling and Evaluation

Model Training
- DecisionTree
- RidgeRegression
- LinearRegression
- XGBoost

Model Evaluation
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Squared Logarithmic Error (MSLE)
- Root Mean Squared Logarithmic Error (RMSLE)

## Predictions

Predicted on Test Dataset

## Installation

```bash
pip install -r requirements.txt
```

### Clone the repository
```bash
git clone <https://github.com/elishastanley/Demand-Forecasting-Optimization-for-Corporation-Favorita-A-Time-Series-Regression-ML-Approach.git>

cd Demand Forecasting Optimization for Corporation Favorita A Time Series Regression ML Approach
```

## Contact

For any queries regarding this project, please contact:

Elisha Stanley - <elishastanley255@gmail.com>

Thank you for visiting this repository, and I hope you find the Machine Learning Project useful!
