# IMDb Movie Rating Prediction

# Overview
This repository contains the code and resources for a machine learning project aimed at predicting IMDb scores for movies available on Films. The goal of this project is to develop a model that accurately estimates the popularity of movies, helping users discover highly rated films that match their preferences.

# Table of Contents
- [Dataset]
- [Data Preprocessing]
- [Feature Engineering]
- [Model Selection]
- [Model Training]
- [Evaluation]


# Dataset
We utilize a dataset containing information about movies, including features like genre, premiere date, runtime, language, and IMDb scores. The dataset is located in the `data` directory and is named `movie_data.csv`.

# Data Preprocessing
In this stage, we perform data cleaning, handle missing values, and convert categorical features into numerical representations to prepare the data for modeling. The code for data preprocessing can be found in the `data_preprocessing.ipynb` notebook.

# Feature Engineering
We extract relevant features from the available data that could contribute to predicting IMDb scores. Feature engineering is a crucial step in improving the model's performance. The feature engineering process is detailed in the `feature_engineering.ipynb` notebook.

# Model Selection
For predicting IMDb scores, we consider several regression algorithms, including Linear Regression and Random Forest Regressor. We select the most appropriate algorithm based on its performance during evaluation.

# Model Training
The selected model is trained using the preprocessed data. Model training code can be found in the `model_training.ipynb` notebook.

# Evaluation
We evaluate the model's performance using regression metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared. The evaluation results are presented in the `model_evaluation.ipynb` notebook.
