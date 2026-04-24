# Loan-Default-Prediction-using-ANN-DL-
In this project we used ANN (Deep learning)

# Project Overview

This project focuses on predicting whether a customer will default on a loan using an Artificial Neural Network (ANN).
The goal is to build a robust classification model that can help financial institutions assess risk and make better lending decisions.

# Dataset Description

The dataset contains customer financial and personal information used to predict loan default.
🔹 Features:
Age – Age of the customer
Income – Annual income
LoanAmount – Loan amount taken
CreditScore – Creditworthiness score
MonthsEmployed – Employment duration
NumCreditLines – Number of credit lines
InterestRate – Loan interest rate
LoanTerm – Duration of loan
DTIRatio – Debt-to-income ratio

🔹 Categorical Features:
Education
EmploymentType
MaritalStatus
HasMortgage
HasDependents
LoanPurpose
HasCoSigner

Target Variable:
Default
1 → Loan Default
0 → No Default

# Technologies Used
Python
TensorFlow / Keras → Deep Learning model
Pandas → Data handling
Scikit-learn → Preprocessing & splitting
Matplotlib → Visualization

# Project Workflow
1️⃣ Data Loading
Dataset loaded using Pandas
2️⃣ Data Preprocessing
Split into:
X (features)
y (target)
Numerical features → Standardized using StandardScaler
Categorical features → Encoded using OneHotEncoder
3️⃣ Train-Test Split
80% Training data
20% Testing data
4️⃣ Feature Engineering Pipeline
Used ColumnTransformer to handle:
Numerical scaling
Categorical encoding
5️⃣ Model Building (ANN)
Input Layer: 31 features
Hidden Layer: 16 neurons (ReLU)
Output Layer: 1 neuron (Sigmoid)
6️⃣ Model Compilation
Loss Function: Binary Crossentropy
Optimizer: Adam
Metric: Accuracy
7️⃣ Model Training
Trained for 10 epochs
Used validation data to monitor performance

# Model Performance
🔹 Metrics Tracked:
Training Accuracy
Validation Accuracy
Training Loss
Validation Loss
🔹 Interpretation:
Accuracy increases over epochs → Model is learning
Loss decreases → Error is reducing
Comparison of training & validation:
Helps detect overfitting / underfitting

👉 (You can add your final accuracy here, for example:)

Final Training Accuracy: 88.63 %
Final Validation Accuracy: 88.71 %


