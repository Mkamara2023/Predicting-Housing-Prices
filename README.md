# Predicting-Housing-Prices
This project aims to predict housing prices using a linear regression model on the California Housing dataset. The dataset contains various features such as housing median age, total rooms, total bedrooms, population, households, median income, and ocean proximity.
Steps Taken:
Data Loading and Cleaning:

Loaded the housing dataset using Pandas.
Dropped rows with missing values.
Data Preprocessing:

Encoded categorical features using one-hot encoding.
Split the data into features and target variable.
Split the data into training and testing sets (80% train, 20% test).
Model Building and Evaluation:

Trained a Linear Regression model using scikit-learn.
Made predictions on the test set and evaluated model performance using Mean Squared Error.
Visualizations:

Created a scatter plot to visualize the relationship between actual and predicted house values.
Generated a histogram showing the distribution of median house values.
Displayed histograms for each numerical feature to understand their distributions.
