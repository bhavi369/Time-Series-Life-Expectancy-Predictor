# Time-Series-Life-Expectancy-Predictor
Predict life expectancy using time series data. Compare models (Random Forest, Linear Regression, Auto ARIMA), analyze population trends, and explore influential factors for insightful predictions.

# Overview:
The project revolves around predicting life expectancy using historical time series data. It employs a range of techniques including time series analysis, Random Forest Regression, and Linear Regression. The dataset used includes information about population size, region, income group, and life expectancy across various countries from 1960 to 2021.

# Methodology:
## Data Preprocessing: 
The initial step involves loading, cleaning, and merging datasets related to life expectancy and population. This process includes handling missing values and structuring the data for analysis.

## Exploratory Data Analysis (EDA): 
The EDA phase focuses on understanding the data's distribution, summary statistics, and identifying trends. It selects countries based on population size and examines population trends over time.

## Time Series Analysis:
Time series analysis is conducted for population and life expectancy in different countries. This includes visualizing trends, autocorrelation, partial autocorrelation functions, and ARIMA modeling.

## Model Development and Evaluation: 
The project builds Random Forest and Linear Regression models to predict life expectancy. These models are trained and evaluated using a combination of countries' data, comparing their accuracy metrics and predictive capabilities.

# Key Insights:
## Population Trends:
Analysis reveals increasing population trends across selected countries (e.g., China, Finland, and Tuvalu) over the studied period.

## Model Performance: 
The Random Forest model demonstrates superior performance compared to Linear Regression in predicting life expectancy. It outperforms in terms of accuracy metrics, such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and Mean Absolute Error (MAE).

## Critical Predictor: 
Population size emerges as the most significant predictor of life expectancy based on the Random Forest model's feature importance analysis. It contributes significantly to predicting life expectancy, showcasing its strong influence.

ARIMA Modeling: Auto ARIMA modeling reveals predictive capabilities for both population and life expectancy, providing insights into future trends.

Conclusion:
The project successfully explores the potential of historical time series data in predicting life expectancy. It establishes that population size is a crucial factor influencing life expectancy trends across various countries. The Random Forest model stands out as the preferred choice for accurate life expectancy predictions.
