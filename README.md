# Regression Project - Time-Series Analysis and Modeling
The repository provides all the necessary code and data to reproduce the project's results.


## Introductions and Overview
----
This project focuses on time series analysis and modeling using regression techniques. Time series data is an essential part of various domains such as finance, economics, and weather forecasting. Time series modeling helps to identify patterns and trends in data, which can help in making future predictions.

## Goal
----
The main goal of this project is to build a regression model that can accurately predict future values of a time series dataset. 


## Hypothesis
----
### 1
- H0 - The type of day does not play a significant role in determining the demand for oil

- H1 - the type of day play a significant roles in determining the demand for oil

### 2
- H0 - The location does not have an impact for the for the demand for oil

- H1 - The location have an impact for the demand for oil

### 3
- H0 - There is no significant correlation between oil price and increase sales

- H1 - There is significant correlation between oil price and increase sales



## Questions
----
1. Is the train dataset complete (has all the required dates)?

2. Which dates have the lowest and highest sales for each year?

4. Are certain groups of stores selling more products? (Cluster, city, state, type)

5. Are sales affected by promotions, oil prices and holidays?

7. What analysis can we get from the date and its extractable features?

8. What is the difference between RMSLE, RMSE, MSE (or why is the MAE greater than all of them?)

9.  What is the relationship between oil prices and sales?

10. What is the relationship between product and sales?

11. What is the trend of sales overtime?

12. What is the relationship between oil prices and promotion?


## Datasets
----
*Train.csv*: Training data with time series for "store_nbr," "family," "onpromotion," and "sales."

*Test.csv*: Similar data for prediction purposes.

*Sample_submission.csv*: A sample submission file in the correct format.

*Transaction.csv*: Contains dates, store_nbr, and transactions.

*Stores.csv*: Store metadata.

*Oil.csv*: Daily oil prices.

*Holidays_events.csv*: Information on holidays and events.

## Steps
----
To achieve this goal, the project will follow the following steps:

Data collection: Collect the time series data from a reliable source. The dataset should have enough historical data to build a robust model.

- Data preprocessing: Clean and preprocess the data by removing any missing values, outliers, and data inconsistencies. This step is essential to ensure the accuracy of the model.

- Exploratory data analysis: Explore the dataset to identify patterns and trends. This step involves plotting the data, calculating statistics, and conducting hypothesis tests.

- Feature engineering: Extract relevant features from the time series data that can help in predicting future values.

- Model selection: Select the appropriate regression model that can accurately predict future values. This step involves comparing various regression models such as linear regression, Decision Tree Model, XGBoost and Random Forest Regresion Models.

- Model training: Train the selected regression model using the preprocessed data.

- Model evaluation: Evaluate the accuracy of the trained model using evaluation metrics such as mean squared error, root mean squared error, and R-squared.


## Technologies Used
----
This project uses the following technologies:

- Python 3.0
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn


## Contribution
----
If you would like to contribute to this repository, please fork the repository and create a pull request with your changes. Contributions are welcome in the form of new data, bug fixes, or new analysis.


## Article
----
Title         | Description  | Link        |
------------- | -------------|-------------|
Regression Project - Time Series Analysis and Modeling | An Article on Regression Time Series Analysis  |https://medium.com/@kwabenaabrefa/regression-project-time-series-analysis-and-modeling-c5e2fab1047c |
 

## Conclusion
----
Time series analysis and modeling are essential in making accurate predictions for various applications. This project demonstrates the process of building a regression model for time series data. By following the steps outlined in this project, you can build robust models that accurately predict future values.

## Author
----
Foster Nana Kwabena Abrefa
