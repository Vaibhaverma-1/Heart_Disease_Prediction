### Overview
The Heart Disease Prediction project aims to compare the performance of three popular machine learning algorithms: K-Nearest Neighbors (KNN), Random Forest, and Logistic Regression. The goal is to determine which algorithm performs best in predicting the presence of heart disease based on various health metrics. Through this analysis, we found that Logistic Regression outperforms the other models in terms of accuracy and interpretability.

### Dataset
The dataset used in this project is sourced from the UCI Machine Learning Repository. It contains various medical attributes and demographic information relevant to heart disease prediction. You can access the dataset using the following link:

Heart Disease UCI Dataset

### Features
The dataset includes the following features:

Age
Sex
Chest Pain Type
Resting Blood Pressure
Serum Cholesterol
Fasting Blood Sugar
Resting Electrocardiographic Results
Maximum Heart Rate Achieved
Exercise Induced Angina
Oldpeak
Slope of the Peak Exercise ST Segment
Number of Major Vessels
Thalassemia
Target Variable (Presence of Heart Disease)

### Algorithms Compared
K-Nearest Neighbors (KNN): A simple, instance-based learning algorithm that classifies data points based on the majority class of their nearest neighbors.

Random Forest: An ensemble learning method that constructs multiple decision trees and merges them to improve accuracy and control overfitting.

Logistic Regression: A statistical model that uses a logistic function to model a binary dependent variable, providing probabilities for class membership.

### Results
The performance of each algorithm was evaluated using metrics such as accuracy, precision, recall, and F1-score. The results indicate that Logistic Regression consistently outperformed KNN and Random Forest in predicting heart disease, making it a reliable choice for this specific application.

### Technologies Used
Python
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
Jupyter Notebook / Google Colab
