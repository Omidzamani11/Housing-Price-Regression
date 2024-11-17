# Housing-Price-Regression
"A project to predict house prices based on features like area, rooms, and location. Includes data preprocessing, feature engineering, and multiple regression models (Linear, Ridge, Lasso, ElasticNet), evaluated using RMSE, MAE, and R² to find the best model for accurate predictions."
House Price Prediction
Overview
This project aims to predict house prices based on various property features like area, number of rooms, and location. We use data preprocessing, feature engineering, and multiple regression models to identify the best model for accurate predictions.

Dataset
The dataset used is the Ames Housing Dataset, featuring 79 characteristics of residential homes in Ames, Iowa.

Train dataset: for training models
Test dataset: for evaluating models
Goals
Implement and compare regression models.
Identify the most effective model for predicting house prices.
Learn and apply data preprocessing, feature engineering, and model evaluation techniques.
Models Used
Linear Regression
Ridge Regression
Lasso Regression
ElasticNet
Evaluation Metrics
Each model is evaluated on:

RMSE: Root Mean Squared Error
MAE: Mean Absolute Error
R²: R-squared
Results:
Model	            RMSE	     MAE	    R²
Linear Regression	0.1741	0.1213	0.8375
Ridge Regression	0.1741	0.1212	0.8376
Lasso Regression	0.2057	0.1424	0.7732
ElasticNet	0.1872	0.1285	0.8122
Project Structure
data/: Contains training and test datasets.
notebooks/: Jupyter notebook for data exploration, modeling, and evaluation.
scripts/: Python scripts for data preprocessing, model training, and evaluation
Installation and Setup
git clone https://github.com/username/House-Price-Prediction.git
pip install -r requirements.txt
jupyter notebook notebooks/House_Price_Prediction.ipynb
Key Takeaways
Data Preprocessing: Addressing missing values and encoding categorical features.
Model Comparison: Analyzing results across different regression models.
