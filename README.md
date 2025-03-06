# Prediction System of Crops with AWS SageMaker, Machine Learning
## Overview
The Prediction System of Crops with Machine Learning aims to assist farmers in identifying the most suitable crop based on soil composition and climatic conditions. By applying machine learning techniques, this project evaluates different crop types and recommends the best option to increase agricultural yield and productivity.

The project incorporates a dataset from Kaggle, performs comprehensive data analysis and visualization, and builds several predictive models to find the best-performing approach. The results showcase the potential of precision agriculture in optimizing farming practices.

# Features
Data Analysis and Visualization: Insights into soil and climatic attributes, including correlation and distribution analysis.
Significant Predictors: Identified key features such as Nitrogen, Phosphorus, Potassium, Humidity, and pH, using multiple regression.
Modeling Techniques:
K-Nearest Neighbors (KNN)
Decision Tree
Random Forest
XGBoost
Naive Bayes
Support Vector Machines (SVM)
Accuracy Comparison: XGBoost emerged as the most accurate model, achieving a prediction accuracy of 95.59%.
# Dataset
The dataset comprises 22 crop types and their associated parameters, including:

Soil composition (Nitrogen, Phosphorus, Potassium, pH)
Climatic factors (Humidity, Rainfall, Temperature)
The data was cleaned and prepared, ensuring no null values or outliers, and encoded for machine learning models.

# Steps Completed
Data Preprocessing: Renaming columns, handling missing values, and encoding categorical data.
Visualization: Correlation heatmaps, histograms, and joint plots to explore relationships between variables.
Feature Scaling: Used MinMaxScaler for improved model performance.
Model Training and Testing:
Split data into 75% training and 25% testing sets.
Evaluated models based on cross-validation scores.
# Results
Random Forest: 95.41% Accuracy
XGBoost: 95.59% Accuracy (Best performing model)
The XGBoost model was selected for its higher precision and faster computation times compared to other methods.

# Future Scope
While the system provides accurate predictions, it can be extended to include:

Real-time data integration for dynamic recommendations.
Geolocation-based suggestions for regional crops.
Deployment as a web or mobile application for farmers.
