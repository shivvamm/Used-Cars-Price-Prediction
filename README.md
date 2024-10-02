# Kaggle Playground Series: Used Cars Price Prediction

For the 2024 Kaggle Playground Series competition! In this challenge, the goal was to predict the price of used cars based on various attributes. This README outlines my approach, the techniques used, and how to navigate the Jupyter notebook provided.

## Competition Overview

- **Competition Name:** Kaggle Playground Series - Used Cars Price Prediction
- **Start Date:** September 1, 2024
- **Final Submission Deadline:** September 30, 2024
- **Evaluation Metric:** Root Mean Squared Error (RMSE)

## Dataset

The dataset consists of synthetic data generated from real-world used car attributes. It includes various features relevant to car pricing, which we will leverage for our model.

## Approach

### 1. Data Exploration

- Analyzed the dataset to understand the distribution of features and target variable.
- Identified missing values and outliers.
- Visualized relationships between features and the target variable using plots.

### 2. Feature Engineering

- **Scaling:** Applied normalization and standardization techniques to scale the features for better model performance.
- **Feature Extraction:** Created new features based on existing ones, such as combining year and mileage for better context.

### 3. Model Selection

- **Random Forest:** Implemented a Random Forest Regressor due to its effectiveness in handling non-linear relationships and robustness against overfitting.

### 4. Model Training and Evaluation

- Split the dataset into training and validation sets.
- Trained the model on the training set and evaluated it using RMSE on the validation set.
- Tuned hyperparameters to optimize performance.

## Jupyter Notebook

The Jupyter notebook `Used_Cars_Price_Prediction.ipynb` contains the complete implementation of the above approach, including:

- Data loading and preprocessing
- Exploratory data analysis (EDA)
- Feature engineering techniques
- Model training and evaluation
- Predictions on the test set

### Instructions to Run the Notebook

1. Clone this repository:
   ```bash
   git clone https://github.com/shivvamm/Used-Cars-Price-Prediction.git
   cd Used-Cars-Price-Prediction

2. Downlod the Train and Test Dataset:

     - [Used Cars Train and Test](https://www.kaggle.com/datasets/shivvamm/used-cars)