# ml-project

This project provides a comparison of different supervised learning models to predict churn behavior/fraud/customer attrition on 3 different datasets dealing with unbalanced data.

The project uses the following datasets from Kaggle :

- [Credit Fraud](https://www.kaggle.com/code/janiobachmann/credit-fraud-dealing-with-imbalanced-datasets)
- [Bank Marketing](https://www.kaggle.com/code/henriqueyamahata/bank-marketing-imbalanced-dataset-94)
- [Employee Attrition](https://www.kaggle.com/code/junglisher/employee-attrition-analysis/input) 

The main steps of the project are outlined below for each dataset, each session was conducted in a seperate notebook:

- **Session 1 - Exploratory Analysis of Imbalanced Data** : Visualization of churn vs. non-churn proportions for categorical and numerical variables, Correlation matrix of all features, Identification of attributes strongly correlated with churn behavior and of most influential variables for each dataset
- **Session 2: Churn Prediction (Part I)** : Comparaison of Decision Tree, Logistic Regression and SVM (with and without kernels) models on the default hyperparameters as well as performing hyperparameter tuning through Grid Search, evaluating predictions on AUC 
- **Session 3: Churn Prediction (Part II)** : Comparaison of 2 additional models Random Forest and XGBoost on the default hyperparameters as well as performing hyperparameter tuning through Grid Search, evaluating predictions on AUC. Identification of the most important features for each model previously built
- **Session 4: Oversampling and Undersampling** : Use of Oversampling and Undersampling methods, comparing the impact of resampling techniques on the performance of each algorithm

This project was completed as part of the course Machine Learning for Data Science at University Paris Cité, France. Therefore the comments and analysis are written in French, except for the pdf report which has been translated.

# Repository Overview
This repository contains 4 Jupyter notebooks, one for each session, [ML_Seance1](ML_Seance1.ipynb), [ML_Seance2](ML_Seance2.ipynb), [ML_Seance3](ML_Seance3.ipynb), [ML_Seance4](ML_Seance4.ipynb) and an [original version of the report in French](ML_Report%20%28Original%20version%29.pdf) as well as a [translated version of the report](ML_Report%20%28Translated%29.pdf).
