# SONAR-Rock-vs-Mine-Prediction

This project utilizes machine learning to classify SONAR signals as either rocks or mines. The dataset contains signals bounced off different objects, and the goal is to accurately determine whether the object is a rock or a mine based on the signal features. The classification is done using a logistic regression model.

=> Project Overview
The dataset used for this project contains 208 samples with 60 features, where each feature represents the energy level in different frequency bands. The target label is binary: 'R' for rocks and 'M' for mines. This project includes the following steps:

=> Data Collection and Preprocessing
- Exploratory Data Analysis (EDA)
- Splitting the dataset into training and test sets
- Building and training the logistic regression model
- Evaluating model performance

=> Steps in the Project
1. Data Collection and Preprocessing
The data is loaded from a CSV file without headers. It is then split into features (X) and labels (Y).
Feature scaling or normalization is not performed as logistic regression handles that internally.
The dataset is split into training and test sets using an 80-20 split.
2. Model Building
A Logistic Regression model is chosen for its simplicity and efficiency in binary classification tasks.
The training data is used to fit the model, and the test data is used for evaluation.
3. Model Evaluation
The accuracy score of the model is calculated using the test set. This metric helps us understand the model's performance in distinguishing between rocks and mines.
