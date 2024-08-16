# Predictive Modeling

## Overview

This project focuses on predicting the fatigue life of materials using various machine learning regression models. The objective was to implement, validate, and compare multiple models to identify the best-performing one. The project involved extensive feature engineering and exploratory data analysis (EDA) to optimize the prediction accuracy.

## Models Implemented

- **K-Nearest Neighbors (KNN) Regression**
- **Support Vector Regression (SVR)**
- **Random Forest Regression**
- **Neural Network**

Among these, **Random Forest** was identified as the best-performing model with an accuracy of **89%** in predicting fatigue life.

## Feature Engineering

- **Pearson Correlation Matrix**: Used to assess the correlation between features, which helped in selecting the most relevant features.
- **Exploratory Data Analysis (EDA)**: Conducted to understand the data distribution, identify outliers, and detect patterns that could improve model performance.

## Project Structure

- `main.ipynb`: The main Jupyter Notebook containing the implementation of all models, feature engineering, and model validation.
- `data/`: Directory containing the dataset used for model training and testing.
- `results/`: Directory containing the results of model performance metrics and visualizations.

## How to Run the Project

1. Clone the repository to your local machine.
   ```bash
   git clone https://github.com/yourusername/predictive-modeling-ml.git
2. Navigate to the project directory.
   ```bash
   cd predictive-modeling-ml
3. Install the required dependencies.
   ```bash
   pip install -r requirements.txt
4. Open the Jupyter Notebook and run all cells to see the model training and validation steps.
   ```bash
   jupyter notebook main.ipynb
## Results

The Random Forest model was identified as the best predictor for fatigue life with an accuracy of 89%. The model outperformed KNN, SVR, and Neural Network models due to its ability to handle non-linear data and feature interactions effectively.

## Conclusion

This project demonstrates the importance of model selection, feature engineering, and thorough validation in building robust predictive models. The Random Forest model's high accuracy makes it a reliable tool for predicting fatigue life, which could be beneficial in various engineering applications.

