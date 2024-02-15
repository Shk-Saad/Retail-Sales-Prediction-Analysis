# Retail-Sales-Prediction-Analysis
This project demonstrates how various regression techniques can be utilized to predict sales in a retail business and provides insights into the factors influencing sales performance.

This project focuses on predicting monthly sales for a retail business based on various factors such as advertising spending, number of employees, and online presence. The data is obtained from a retail dataset and analyzed using Python's pandas, numpy, matplotlib, and seaborn libraries. 

Initially, the dataset is loaded and explored to understand its structure and characteristics. Data cleaning steps, such as removing unnecessary columns, are performed. Then, correlation analysis is conducted to identify relationships between different variables.

Simple linear regression is used to model the relationship between advertising spending and monthly sales. The data is split into training and testing sets, and a linear regression model is trained on the training data. The model's performance is evaluated using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared.

Furthermore, multiple linear regression is employed to incorporate additional predictors such as the number of employees and online presence into the model. The model is trained using the three predictors and their interactions. The coefficients and intercept of the model are analyzed to understand the impact of each predictor on monthly sales.

Additionally, polynomial regression is applied to capture non-linear relationships between predictors and the target variable. A polynomial feature transformation is performed on the training data, and a linear regression model is trained on the transformed features. The coefficients of the polynomial regression model are examined to understand the polynomial terms' contributions to the prediction.
