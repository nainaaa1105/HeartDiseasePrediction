Heart Disease Prediction Model 

This project implements a Heart Disease Prediction System using Machine Learning to estimate the risk of heart disease based on key clinical and demographic attributes. The model assists in early risk assessment by analyzing patient health indicators and providing a binary prediction: High Risk or Low Risk.

Dataset & Features:

The model is trained on a structured cardiovascular dataset containing both numerical and categorical features, including:

Age

Sex

Chest Pain Type

Resting Blood Pressure

Cholesterol Level

Fasting Blood Sugar

Resting ECG Results

Maximum Heart Rate

Exercise-Induced Angina

ST Depression (Oldpeak)

ST Slope

Categorical variables are one-hot encoded, and numerical features are standardized to ensure uniform scaling.

-> Model Architecture

Algorithm: Logistic Regression

Reason for Selection:

Interpretable coefficients

Efficient for binary classification

Performs well on medical tabular data

The model outputs a probability score, which is thresholded to classify patients into high-risk or low-risk categories.

-> Data Preprocessing

Handling of categorical features using One-Hot Encoding

Feature scaling using StandardScaler

Column alignment to maintain consistency during inference

Model and preprocessing objects saved using Joblib

-> Evaluation Metrics

The model is evaluated using:

Accuracy

Precision

Recall

F1-Score

These metrics ensure balanced performance, especially for detecting high-risk cases where false negatives are critical.

-> Deployment

The trained model is deployed using Streamlit, allowing users to:

Input patient health parameters through an interactive UI

Receive instant predictions with risk categorization

View results in a user-friendly, web-based application

-> Outcome

This system provides a fast, interpretable, and reliable approach for early heart disease risk prediction, making it suitable for educational use, hackathons, and prototype-level healthcare applications.
