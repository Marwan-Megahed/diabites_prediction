# diabites_prediction

This project, encapsulated in the final_diabites.ipynb Jupyter Notebook, is a comprehensive data science endeavor aimed at predicting the likelihood of a person having diabetes. It takes you through the entire machine learning pipeline, from data cleaning and exploratory analysis to model training and evaluation.

Project Overview
The main objective is to build and compare several machine learning models to accurately predict diabetes based on various health metrics. A key part of the process involves addressing class imbalance in the dataset using the SMOTE (Synthetic Minority Over-sampling Technique) algorithm to ensure the models are trained on a balanced dataset and provide reliable predictions. The project concludes by evaluating and comparing the performance of multiple classification algorithms to identify the most effective one.

Dataset
The analysis uses the diabetes_prediction_dataset.csv file, which contains 100,000 entries and 9 key columns:

gender

age

hypertension

heart_disease

smoking_history

bmi

HbA1c_level

blood_glucose_level

diabetes (The target variable)

Methodology
The project follows a structured methodology to ensure a robust and reliable model:

Data Preprocessing: The dataset is loaded and cleaned by removing duplicate entries. Categorical features like gender and smoking_history are encoded into a numerical format suitable for machine learning algorithms.

Handling Imbalance: The diabetes target variable has a significant class imbalance, which is resolved by applying the SMOTE technique to the training data.

Model Training: The data is split, and a variety of classification models are trained, including:

Logistic Regression

Support Vector Classifier (SVC)

K-Nearest Neighbors Classifier

Decision Tree Classifier

Gaussian Naive Bayes

Random Forest Classifier

Gradient Boosting Classifier

Model Evaluation: Each model's performance is evaluated using standard metrics from a confusion matrix and a classification report to assess accuracy, precision, recall, and F1-score.

Results
The notebook compares the performance of all trained models, providing a clear visualization and a detailed report. The final conclusion identifies the best-performing model for this specific diabetes prediction task.
