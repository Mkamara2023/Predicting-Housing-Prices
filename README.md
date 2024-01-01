# Housing Price Prediction Project

This project focuses on predicting housing prices using a linear regression model on the California Housing dataset. The dataset comprises various features, including housing median age, total rooms, total bedrooms, population, households, median income, and ocean proximity.

## Project Overview

The project aims to accomplish the following steps:

### Data Preprocessing
- Load the housing dataset from a CSV file.
- Drop rows with missing values to ensure clean data.
- Encode categorical features using one-hot encoding.
- Split the data into features (X) and the target variable (y).

### Model Building
- Split the data into training and testing sets (80% train, 20% test).
- Train a Linear Regression model using the training data.
- Make predictions on the test set and evaluate model performance using Mean Squared Error (MSE).

### Visualization
- Visualize the relationship between the actual and predicted house values using a scatter plot.
- Display the distribution of median house values through a histogram.
- Create individual histograms for numerical features to understand their distributions.

## Tools Used
- Python
- Pandas for data manipulation
- Matplotlib for data visualization
- Scikit-learn for machine learning modeling

## Instructions
1. Clone or download this repository to your local machine.
2. Ensure you have Python installed along with necessary libraries (Pandas, Matplotlib, Scikit-learn).
3. Run the provided code in your Python environment to observe the housing price prediction analysis.
