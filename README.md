<h1 align="center">House Sales Price Prediction Using Machine Learning Regression Models</h1>
<p align="center">
<img src="Hr image.png">


## Project Overview
The goal of this project is to predict the sales price of houses using various machine learning techniques. The project involves preprocessing the data, selecting important features, building and tuning models, and evaluating their performance.<br>

The project is structured as follows:<br>
• Read CSV File: Load the training and testing datasets.<br>
• Check Missing Values: Identify and handle missing values.<br>
• Decide Strategy for Continuous and Categorical Features: <br>
Impute missing values for continuous features using the mean strategy and for categorical features using the most frequent or constant strategy.<br>

#### Sklearn Pipeline:<br>
• Feature Selection: Select important features using forward or backward selection with Linear Regression.<br>
• Final Pipeline: Create a pipeline for preprocessing and model building.<br>
• Train-Test Split: Split the data into training and testing sets.<br>
• Final Model Building: Build and tune Ridge and Lasso regression models using GridSearchCV.<br>
• Model Prediction: Predict house prices for the training and testing sets.<br>
• Model Evaluation: Evaluate the models using MSE, RMSE, MAE, R².<br>
• Predict Testing Set: Predict the house prices for the provided test set.<br>

#### Metrics<br>
The models are evaluated using the following metrics:<br>
• Mean Squared Error (MSE)<br>
• Root Mean Squared Error (RMSE)<br>
• Mean Absolute Error (MAE)<br>
• R² (R-squared)<br>

#### Data<br>
The data for this project includes the following files:<br>
training_set.csv: The training dataset containing house features and sale prices.<br>
testing_set.csv: The testing dataset for which house prices need to be predicted.<br>

#### Libraries used<br>
• pandas<br>
• numpy<br>
• scikit-learn<br>
