<h1 align="center">House Sales Price Prediction Using Machine Learning Regression Models</h1>
<p align="center">
<img src="Hr image.png">


## Project Overview
The goal of this project is to predict the sales price of houses using various machine learning techniques. The project involves preprocessing the data, selecting important features, building and tuning models, and evaluating their performance.<br>

The project is structured as follows:
• Read CSV File: Load the training and testing datasets.
• Check Missing Values: Identify and handle missing values.
• Decide Strategy for Continuous and Categorical Features: Impute missing values for continuous features using the mean strategy and for categorical features using the most frequent or constant strategy.<br>

#### Sklearn Pipeline:
• Feature Selection: Select important features using forward or backward selection with Linear Regression.
• Final Pipeline: Create a pipeline for preprocessing and model building.
• Train-Test Split: Split the data into training and testing sets.
• Final Model Building: Build and tune Ridge and Lasso regression models using GridSearchCV.
• Model Prediction: Predict house prices for the training and testing sets.
• Model Evaluation: Evaluate the models using MSE, RMSE, MAE, R²
• Predict Testing Set: Predict the house prices for the provided test set.

#### Metrics
The models are evaluated using the following metrics:
• Mean Squared Error (MSE)
• Root Mean Squared Error (RMSE)
• Mean Absolute Error (MAE)
• R² (R-squared)

#### Data
The data for this project includes the following files:
training_set.csv: The training dataset containing house features and sale prices.
testing_set.csv: The testing dataset for which house prices need to be predicted.

#### Libraries used
• pandas
• numpy
• scikit-learn
