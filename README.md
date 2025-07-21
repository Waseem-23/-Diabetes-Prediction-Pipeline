# -Diabetes-Prediction-Pipeline

🎯 Objective
The goal of this dataset is to predict whether a patient has diabetes based on diagnostic medical attributes. It is a binary classification problem.


 Work Summary
Problem Defined: Predict whether a patient has diabetes (binary classification).

Dataset Used: Pima Indians Diabetes Dataset (768 records, 8 features).

Data Cleaning:

Replaced invalid zero values in Glucose, BloodPressure, BMI, SkinThickness, and Insulin with median values.

Exploratory Data Analysis (EDA):

Visualized class imbalance and feature correlations using plots and heatmaps.

Data Preprocessing:

Split into training (80%) and testing (20%) sets.

Scaled features using StandardScaler.

Model Training:

Trained two models: Logistic Regression and K-Nearest Neighbors (KNN).

Model Evaluation:

Evaluated using Accuracy, Precision, and Recall.

Logistic Regression achieved ~75% accuracy; KNN ~72%.

Gradio Web App:

Built an interactive app for real-time diabetes prediction using user input and selected model.

