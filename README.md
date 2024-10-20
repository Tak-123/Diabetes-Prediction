# Diabetes-Prediction
This project aims to build a Diabetes Prediction System using machine learning algorithms. The model predicts whether a patient is likely to have diabetes based on various medical attributes. The goal is to assist healthcare providers in identifying at-risk patients and providing early interventions.
Key Features:
Input Features: Utilizes patient data such as age, BMI, glucose levels, insulin levels, blood pressure, and family history to predict diabetes risk.
Algorithms: Implements multiple machine learning models (e.g., Logistic Regression, Random Forest, Support Vector Machine) to perform binary classification (diabetes or no diabetes).
Data Preprocessing: Handles missing data, normalization, and feature scaling to improve model accuracy.
Evaluation Metrics: Evaluates model performance using accuracy, precision, recall, F1-score, and ROC-AUC curve.
Tech Stack:
Programming Language: Python
Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
Dataset: Pima Indians Diabetes Dataset (available from UCI Machine Learning Repository or Kaggle)
How It Works:
Data Collection: The model uses the Pima Indians Diabetes dataset, which contains medical records for patients with and without diabetes.
Data Preprocessing: The data is cleaned by handling missing values, standardizing features, and splitting into training and test sets.
Model Training: The machine learning models are trained on the training data to predict the likelihood of diabetes.
Model Evaluation: After training, the models are evaluated on unseen test data using various performance metrics.
Prediction: The system predicts whether a person has diabetes based on their input medical data.
