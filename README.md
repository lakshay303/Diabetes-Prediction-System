🩺 Diabetes Prediction System

A Machine Learning-based web application that predicts whether a patient is likely to have diabetes based on medical attributes such as Glucose Level, BMI, Blood Pressure, Insulin, Age, and more.

🚀 Project Overview

This project was developed as part of my AI & Machine Learning Internship.

The objective is to build a predictive system that can assist in the early detection of diabetes using machine learning techniques.

📊 Dataset

Dataset: Pima Indians Diabetes Dataset

Features Used:

* Pregnancies
* Glucose
* Blood Pressure
* Skin Thickness
* Insulin
* BMI
* Diabetes Pedigree Function
* Age

Target Variable:

* 0 → Non-Diabetic
* 1 → Diabetic

⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Streamlit
* Joblib

🔍 Machine Learning Workflow

1. Data Collection
2. Data Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Scaling using StandardScaler
5. Model Training using Logistic Regression
6. Model Evaluation
7. Web Application Development using Streamlit

🎯 Model Performance

* Algorithm: Logistic Regression
* Accuracy: 70%

💻 Web Application

The project includes a Streamlit-based web application where users can enter patient information and receive instant diabetes predictions.

📂 Project Structure

Diabetes-Prediction-System/

├── app.py

├── diabetes.csv

├── diabetes_model.pkl

├── scaler.pkl

├── requirements.txt

└── README.md

▶️ How to Run

Install dependencies:

pip install -r requirements.txt

Run the application:

streamlit run app.py

👨‍💻 Author
Lakshay
AI & ML Internship Project
