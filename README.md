# Exercise: Regression Analysis with XGBoost and Hyperparameter Tuning
This repository contains a Jupyter Notebook demonstrating a regression analysis using machine learning models, focusing on XGBoost and hyperparameter tuning to
improve model performance. The goal is to predict outcomes based on a given dataset by fine-tuning model parameters to achieve the best accuracy.

# Project Overview
In this project, we employ the following methods and tools:

Data Preprocessing: Handling missing values and preparing the dataset for model training.
Model Selection: Using the XGBoost algorithm, known for its performance in regression tasks.
Hyperparameter Tuning: Applying RandomizedSearchCV to find the optimal model parameters.
Model Evaluation: Calculating accuracy and selecting the best model based on evaluation metrics.

# Key Libraries Used
pandas: For data manipulation and analysis.
XGBoost: Core regression model used in this analysis.
RandomizedSearchCV: For hyperparameter tuning and cross-validation.
Scikit-learn: To assist with preprocessing and model evaluation.

# Results
The best results achieved by XGBClassifier were 75.5% of accuracy.
Best Model: The best-performing model was obtained with the following hyperparameters: max_depth=2 and max_features=7

# Future Improvements
Testing with more complex models and additional tuning methods.

# License
This project is licensed under the MIT License. See the LICENSE file for details.
