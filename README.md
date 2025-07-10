# RESTAURANT-RATING
1)Project Overview : 
This project aims to develop a machine learning model to predict the aggregate rating of a restaurant based on various features such as location, cost, cuisine type, and service availability. The goal is to help users estimate how well a restaurant is likely to perform based on its attributes.

2)Dataset Summary : 
The dataset includes information on:
Restaurant name and location (city, locality)
Cuisines offered
Price range and average cost for two people
Aggregate rating (target variable)
Online delivery and table booking availability
Geographical coordinates (latitude, longitude)
Target variable: Aggregate rating

3)Project Steps : 
Data Preprocessing
Removed irrelevant or identifier columns
Handled missing values (especially in Cuisines)
Encoded categorical variables using one-hot encoding
Scaled numerical features for consistent model input
Train-Test Split
Data split into training and testing sets (typically 80/20)
Model Selection
Linear Regression
Random Forest Regressor (optional for improvement)
Model Evaluation
Metrics used: Mean Squared Error (MSE), R² Score
Analyzed model performance on test data
Identified the most influential features affecting ratings

4)Technologies Used : 
Python
Pandas and NumPy (data manipulation)
Scikit-learn (modeling and evaluation)
Matplotlib/Seaborn (optional visualization)



