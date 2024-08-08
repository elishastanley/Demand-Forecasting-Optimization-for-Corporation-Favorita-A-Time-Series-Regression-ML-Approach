# Project Title

Demand Forecasting Optimization for Corporation Favorita: A Time Series Regression ML Approach

![Time series Forecast](<images/0JX3-0nZ6nWACUM6E.png>)

## Project Overview

This project aims to optimize inventory management for Corporation Favorita, a large grocery retailer in Ecuador. By developing machine learning models to forecast product demand across various stores, the project seeks to ensure the right quantity of products is always in stock. The key questions address the impact of various factors on sales, including promotions, holidays, and external events. The outcomes include predictive models that aid in inventory decisions, enhancing customer satisfaction and minimizing costs.

## Table of Contents

- [Business Understanding](#business-understanding)
- [Data Collection](#Data-Collection)
- [Data Cleaning](#Data-Cleaning)
- [Exploratory Data Analysis (EDA)](#Exploratory-Data-Analysis)
- [Hypotheses Testing](#Hypotheses-Testing)
- [Power BI Dashboard](#power-bi-dashboard)
- [Analytical Questions](#Analytical-Questions)
- [Modeling and Evaluation](#Modeling-and-Evaluation)
- [Predictions](#Predictions)
- [Saving](#Saving)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#Contributing)
- [License](#License)
- [Contact](#contact)

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

Detail the sources of data, methods of data acquisition, and any initial data handling considerations.

### Data Sources

- **train.csv**: Time series data of store, product information, promotions, and sales.
- **test.csv**: Features similar to the training data for the 15 days following the last date in the training data.
- **transaction.csv**: Daily transactions per store.
- **stores.csv**: Metadata about stores including location and type.
- **oil.csv**: Daily oil prices.
- **holidays_events.csv**: Information about holidays and events, including special designations like transferred, bridge, and workdays.
- **sample_submission.csv**: A sample submission file for formatting predictions.

## Data Cleaning

Explain the steps taken to clean and preprocess the data, including handling missing values, outliers, and data transformation.

## Exploratory Data Analysis (EDA)

Describe the techniques used for exploring the data, including visualizations, statistical summaries, and any initial findings.

## Hypotheses Testing

Outline any hypotheses formed from the data exploration phase and the statistical tests used to confirm or reject them.

## Analytical Questions

List the key questions that guide the analysis and how the data answers these questions.

## Modeling and Evaluation

Discuss the models used, the rationale for their selection, and their performance metrics.

## Predictions

Describe how the model is used to make predictions and any considerations for its implementation.

## Saving

Explain how results, models, or data are saved and stored.

## Installation

Provide instructions on how to set up and run the project, including how to install required software and libraries.

```bash
pip install -r requirements.txt
```

## Clone the repository
```bash
git clone <https://github.com/elishastanley/Demand-Forecasting-Optimization-for-Corporation-Favorita-A-Time-Series-Regression-ML-Approach.git>

cd Demand Forecasting Optimization for Corporation Favorita A Time Series Regression ML Approach
```

## Contact

For any queries regarding this project, please contact:

Elisha Stanley - <elishastanley255@gmail.com>

Thank you for visiting this repository, and I hope you find the Machine Learning Project useful!
