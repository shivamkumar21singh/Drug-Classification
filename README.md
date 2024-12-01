# Drug-Classification

**Overview**

This repository contains the implementation of a Drug Classification Model that predicts the type of medication best suited for an individual based on attributes such as age, blood pressure, cholesterol, sodium-to-potassium ratio, and other relevant factors.

The project evaluates multiple machine learning models and performs hyperparameter tuning to achieve optimal accuracy, offering insights into the comparative performance of different approaches.

**Features**

1) Data Preprocessing: Handles missing values, encodes categorical data, and scales numerical features.
2) Exploratory Data Analysis (EDA): Provides insights through visualizations and statistical analysis.
3) Model Training: Trains and compares models including K-Nearest Neighbors (KNN), Logistic Regression, Naive Bayes, and Random Forest.
4) Hyperparameter Tuning: Implements Grid Search CV to enhance model performance.
5) Evaluation: Measures model accuracy and generates performance metrics.

**Technologies Used**

1) Programming Language: Python
2) **Libraries:**
   1) Data Analysis: Pandas, NumPy
   2) Visualization: Matplotlib, Seaborn
   3) Machine Learning: Scikit-learn

**Results**

The model achieved over 90% accuracy across all tested algorithms. Random Forest with Grid Search CV was the best-performing model, demonstrating the highest predictive accuracy and robustness.

**Future Scope**

Incorporate additional features like genetic data for enhanced predictions.
Experiment with deep learning models for further performance improvements.
Deploy the model as a web application using Flask or Django.
