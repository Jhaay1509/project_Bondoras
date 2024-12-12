Loan Default Prediction Using Machine Learning
This project leverages machine learning to predict loan default risk using real-world data from a peer-to-peer lending company. It addresses data preprocessing, class imbalance, and feature selection while building and evaluating classification models.

Key Features:
Data Loading and Exploration:

Loads loan data from a CSV file and enables full exploration using Pandas for detailed inspection.
Preprocessing Pipeline:

Handles missing values with SimpleImputer.
Scales numerical features using StandardScaler.
Encodes categorical variables with OneHotEncoder.
Imbalance Handling:

Utilizes SMOTE to tackle class imbalance, ensuring reliable model predictions.
Feature Selection:

Applies Recursive Feature Elimination (RFE) and mutual information techniques to identify important features.
Classification Models:

Implements and compares classifiers like Random Forest, AdaBoost, and XGBoost.
Optimizes models with GridSearchCV for better performance.
Performance Evaluation:

Evaluates models with metrics like accuracy, precision, recall, F1 score, ROC-AUC, and confusion matrix visualization.
