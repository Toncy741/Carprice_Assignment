# Carprice_Assignment

* Problem Description:

A Chinese automobile company aspires to enter the US market by setting up their manufacturing unit there and producing cars locally to give competition to their US and European counterparts. They have contracted an automobile consulting company to understand the factors on which the pricing of cars depends. Specifically, they want to understand the factors affecting the pricing of cars in the American market, since those may be very different from the Chinese market. Essentially, the company wants to know:
Which variables are significant in predicting the price of a car
How well those variables describe the price of a car
Based on various market surveys, the consulting firm has gathered a large dataset of different types of cars across the American market.

* Business Goal:

You are required to model the price of cars with the available independent variables. It will be used by the management to understand how exactly the prices vary with the independent variables. They can accordingly manipulate the design of the cars, the business strategy etc. to meet certain price levels. Further, the model will be a good way for the management to
understand the pricing dynamics of a new market.

The goal of this project is to explore the relationships between car prices and various independent variables, and to develop predictive models that can provide valuable insights for understanding and forecasting car pricing dynamics.

Dataset
The project uses the CarPrice Dataset, which includes various features related to car specifications and their corresponding prices.

* Project Structure
Data Loading and Preprocessing:

* Handling missing values
* Encoding categorical variables
* Scaling numerical features
* Splitting data into training and testing sets

* Visualizations
Visualizations are used to better understand the data and model performance. 

* Correlation Heatmap:
Shows the correlation between different features and the target variable (car price).


* Feature Importance Bar Chart:
Displays the importance of each feature as determined by ensemble models like Random Forest and Gradient Boosting.


* Model Performance Comparison: 
Compares R-squared, MSE, and MAE for each regression model.

* Model Implementation:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- Support Vector Regressor (SVR)
Model Evaluation:


Metrics:
R-squared, Mean Squared Error (MSE), Mean Absolute Error (MAE)
Identified best-performing model: Random Forest Regressor
Feature Importance Analysis:

Analysis of key variables affecting car prices
Methods used:
Feature importance scores from Random Forest and Gradient Boosting, correlation analysis
Hyperparameter Tuning:

Objective:
To find optimal hyperparameters and improve model performance

Results
The Random Forest Regressor emerged as the top-performing model.


