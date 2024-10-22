# House-Price-Prediction
## Task Description
The project aims to predict house prices based on different characteristics of houses. Using a dataset containing information about different aspects of real estate, we create a model capable of predicting the price of a house based on its properties.
## Project Objective
The goal of this project is to develop and train a machine learning model that will accurately predict home prices. I aim to not only achieve high accuracy in the predictions, but also visualize the results to better understand the factors that affect real estate prices.
## Technology Overview
The following technologies and libraries are used to implement the project:

- **Python**: The main programming language.
- **Pandas**: For data processing and analysis.
- **NumPy**: For working with multidimensional arrays and math functions.
- **Matplotlib**: For data visualization.
- **Seaborn**: For creating beautiful and informative graphs.
- **Scikit-learn**: For building and evaluating machine learning models:
  - train_test_split: For splitting data into training and test samples.
  - cross_val_score: For cross-validating a model.
  - RandomForestRegressor: For building a regression model.
  - Metrics: mean_squared_error, r2_score, mean_absolute_error to assess the quality of the model.
 
## Project Structure

House-Price-Prediction/
│
├─── data/
│ ├─── train.csv ## Data for model training
│ ├─── test.csv # Data for testing the model
│ └─── data_description.txt # Data description
│
├├─── housepriceprediction.ipynb # Jupyter Notebook with code for training, testing and visualizing results
│
└─── README.md # This file
