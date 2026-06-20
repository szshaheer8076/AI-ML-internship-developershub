Task Objective
Develop a machine learning model to predict whether a patient has heart disease based on medical and clinical attributes. The goal is to compare different classification algorithms and identify the most effective model for heart disease prediction.
Dataset Used
Dataset: Cleveland Heart Disease Dataset
Source: University of California, Irvine
Records: 303 patient records
Features: 13 medical attributes including:
Age
Sex
Chest Pain Type
Resting Blood Pressure
Cholesterol Level
Fasting Blood Sugar
ECG Results
Maximum Heart Rate
Exercise-Induced Angina
ST Depression (Oldpeak)
Slope of ST Segment
Number of Major Vessels (CA)
Thalassemia
Target Variable:
0 = No Heart Disease
1 = Heart Disease
Models Applied
Logistic Regression
Used for binary classification.
Predicts the probability of heart disease occurrence.
Features were standardized using StandardScaler before training.
Decision Tree Classifier
Tree-based classification algorithm.
Configured with a maximum depth of 5.
Provides feature importance analysis for interpretability.
Key Results and Findings
Missing values were identified and handled using median imputation.
The target variable was converted into a binary classification problem.
Exploratory Data Analysis (EDA) revealed:
Distribution of heart disease cases among patients.
Relationship between age and heart disease.
Impact of maximum heart rate on disease occurrence.
Disease prevalence across genders.
Both Logistic Regression and Decision Tree models were trained and evaluated on a test dataset.
Performance was measured using:
Accuracy Score
Confusion Matrix
ROC Curve
AUC (Area Under Curve)
Logistic Regression generally provides stable and reliable performance for medical classification problems.
Decision Tree offers better interpretability through feature importance rankings.
Feature importance analysis identified the most influential factors contributing to heart disease prediction.
ROC and AUC analysis enabled comparison of model discrimination ability across different decision thresholds.
The project demonstrated how machine learning can assist healthcare professionals in early detection and risk assessment of heart disease.

Conclusion:
Machine learning models can effectively predict heart disease using patient health data. Logistic Regression and Decision Tree classifiers both produced useful results, with Logistic Regression typically offering robust predictive performance and Decision Trees providing greater explainability.
