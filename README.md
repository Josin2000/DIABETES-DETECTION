Diabetes Prediction with Support Vector Machine (SVM)

This repository contains a Python script for predicting diabetes using the Support Vector Machine (SVM) algorithm. The script utilizes the PIMA Diabetes Dataset to train an SVM model on historical data and make predictions for future instances.

Overview

Diabetes is a prevalent metabolic disorder with serious health implications if left untreated. Early detection plays a crucial role in mitigating the risk of complications and improving patient outcomes. This project aims to develop a machine learning solution for early diabetes detection, leveraging SVM for accurate prediction based on demographic information, medical history, and clinical measurements.

Features

Data Collection and Analysis: The script loads the PIMA Diabetes Dataset into a pandas DataFrame and performs exploratory data analysis.
Data Preprocessing: Features are standardized using StandardScaler from sklearn.preprocessing to ensure consistency in feature scaling.
Train Test Split: The dataset is split into training and testing sets using train_test_split from sklearn.model_selection.
Model Training: An SVM classifier with a linear kernel is trained on the training data using svm.SVC from sklearn.
Model Evaluation: Accuracy scores are calculated on both the training and testing data using accuracy_score from sklearn.metrics.
Making Predictions: The trained model is used to make predictions for future instances based on standardized input data.
