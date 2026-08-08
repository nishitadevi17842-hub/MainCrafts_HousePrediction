# MainCrafts_HousePrediction
House Price Prediction using Linear Regression on the California Housing Dataset. Includes data exploration, EDA, visualization, preprocessing, model training, predictions, and evaluation using MAE, RMSE, and R² Score with Python, Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn.

# House Price Prediction Using Linear Regression

## 📌 Project Overview

This project focuses on building and evaluating a **Linear Regression model for house price prediction** using the **California Housing Dataset**. The project demonstrates a complete Machine Learning workflow, starting from data loading and exploration to model training, prediction, evaluation, and reporting.

The main objective is to understand how a supervised machine learning algorithm can be applied to predict house prices based on different housing-related features. The project also provides practical experience with Python, data analysis, visualization, and machine learning techniques.

## 🎯 Objective

The objective of this project is to introduce and implement the complete Machine Learning lifecycle. The workflow includes **data loading, exploratory data analysis, preprocessing, train-test splitting, model training, prediction, evaluation, and reporting**.

## 📊 Dataset

The **California Housing Dataset** is used for this project. It contains information about housing characteristics in California. The target variable is **MedHouseVal**, which represents the median house value.

The dataset is loaded using **Scikit-learn**, making the project reproducible without requiring a separate dataset download.

## 🔍 Exploratory Data Analysis

Exploratory Data Analysis (EDA) is performed to understand the structure and characteristics of the dataset. The analysis includes checking the dataset shape, column names, data types, descriptive statistics, and missing values.

Different visualizations are also created, including **histograms, scatter plots, and a correlation heatmap**. These visualizations help identify patterns, distributions, and relationships between the features and house prices.

## 🤖 Machine Learning Model

A **Linear Regression** model is trained using the prepared dataset. The data is divided into training and testing sets using an **80:20 split**. The training data is used to learn relationships between the input features and the target variable, while the testing data is used to evaluate the model on unseen data.

## 📈 Model Evaluation

The model is evaluated using three important regression metrics:

* **Mean Absolute Error (MAE)**
* **Root Mean Squared Error (RMSE)**
* **R² Score**

These metrics provide a clear understanding of the prediction performance of the Linear Regression model.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## 📂 Project Deliverables

* `task1_ml_linear_regression.ipynb` – Complete Jupyter Notebook
* `task1_report.pdf` – Short project report
* `linear_regression_model.pkl` – Saved model (optional)

## 🚀 Future Improvements

The model can be improved by using feature engineering, Ridge or Lasso Regression, Random Forest Regression, Gradient Boosting, and hyperparameter tuning.

## ✅ Conclusion

This project provides practical understanding of the complete Machine Learning workflow while demonstrating how Linear Regression can be used for house price prediction.
