# Churn Prediction Project

## Overview

This project focuses on predicting customer churn using machine learning techniques. The dataset used includes features related to customer behavior, and the goal is to build a model that can effectively identify customers who are likely to churn.

## Project Structure

The project is structured as follows:

- **Data Exploration and Analysis:** Initial exploration and analysis of the dataset to understand its characteristics.
  
- **Data Pre-processing:** Handling missing values, outliers, and applying necessary transformations.

- **Modeling:** Building, training, and evaluating machine learning models for churn prediction.

- **Evaluation:** Comparing the performance of different models and identifying the best-performing one.

- **Conclusion:** Summarizing key findings, observations, and recommendations based on the project analysis.

## Technologies Used

- Python
- Jupyter Notebooks
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost, Imbalanced-learn, etc.

## Results

The final selected model is XGBoost, achieving the following metrics:

- **Accuracy:** 87%
- **Precision (Class 0):** 88%
- **Recall (Class 0):** 97%
- **F1-score (Class 0):** 92%
- **Precision (Class 1):** 80%
- **Recall (Class 1):** 46%
- **F1-score (Class 1):** 58%

## Conclusion and Recommendations

- The XGBoost model outperformed the Random Forest model, especially in terms of recall for Class 1.
  
- Surprisingly, the models performed better without outlier removal and pre-processing, suggesting that the original data distribution contains valuable information.

- Further fine-tuning of hyperparameters and exploring feature engineering techniques could be considered for potential performance improvement.

