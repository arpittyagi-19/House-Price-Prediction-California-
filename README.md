# This is California house price prediction model
# Overview:

This script demonstrates a comprehensive data analysis and regression task using the California housing dataset. It covers various aspects from data loading, preprocessing, visualization, model training using XGBoost Regressor, to evaluating and visualizing predictions.

# Description:

The script showcases the following major steps:

*  Data Loading: Fetches the California housing dataset and loads it into a Pandas DataFrame.
*  Data Exploration: Provides insights into the dataset by displaying its shape, checking for missing values, and computing statistical measures like mean, median,  variance, etc.
*  Correlation Analysis: Investigates the correlation between different features using a heatmap.
*  Data Preparation: Splits the data into input features (x) and target (y) and further divides it into training and test sets.
*  Model Training: Utilizes XGBoost Regressor for model training on the training set.
*  Model Evaluation: Assesses the trained model's performance by computing R-squared error and Mean Absolute Error for both training and test data.
*  Visualizations: Presents visualizations comparing actual prices with predicted prices for both training and test datasets.

# Features:

*  NumPy & Pandas: For data manipulation and analysis.
*  Matplotlib & Seaborn: For data visualization and plotting.
*  Scikit-learn: Provides datasets, train-test splitting, metrics for model evaluation.
*  XGBoost: Utilized for regression modeling.

# Usage:
Ensure you have the required libraries installed (numpy, pandas, matplotlib, seaborn, scikit-learn, xgboost) in your Python environment. Run the script in an environment that supports Python. Make sure the dataset path or source is correctly defined.

# How to Use:

*  Install necessary libraries using pip install.
*  Ensure the correct dataset path or source is set up for fetching the California housing dataset.
*  Execute the script in a Python environment.
*  Review the outputs and visualizations to understand the dataset and model performance.

# Notes:

*  The script includes extensive comments for each code section to explain its purpose.
*  Ensure the correct dataset path or source is specified for fetching or loading the California housing dataset.
*  Visualizations aid in understanding correlations and model performance.
*  Model evaluation metrics such as R-squared error and Mean Absolute Error are computed to assess model performance.
