# 📉 Customer Churn Prediction Web App

This project is a Customer Churn Prediction System that uses Machine Learning to predict whether a customer is likely to leave a telecom service. The model is deployed as an interactive web application using Streamlit.

## 🚀 Features

- Predicts customer churn (Yes/No) based on input features

- Trained using Machine Learning algorithms

- User-friendly Streamlit web interface

- Pre-trained model and scaler for fast predictions

- Real-world Telco Customer Churn dataset

## 🧠 Machine Learning Models Used

- Logistic Regression

- Random Forest Classifier

- StandardScaler for feature scaling

- Model training and evaluation are performed in the Jupyter Notebook.

## 📊 Dataset

- Source: Telco Customer Churn Dataset

- Format: CSV

- Target Variable: Churn (Yes / No)

The dataset includes customer details such as:

- Demographics

- Account information

- Services subscribed

- Billing details

## 🖥️ Web Application

The application is built using Streamlit and runs locally.

Run the App Locally
`streamlit run app1.py`


Then open your browser and go to:

link : http://localhost:8501/

## ⚙️ Installation & Setup
- 1️⃣ Clone the Repository
git clone https://github.com/ShreyaDalvi13/customer-churn-prediction.git
cd customer-churn-prediction

- 2️⃣ Install Required Libraries
`pip install -r requirements.txt`


## Main Libraries Used:

- pandas

- numpy

- scikit-learn

- matplotlib

- seaborn

- streamlit

- pickle

## 📈 Model Performance

The model is evaluated using:

- Accuracy Score

- Confusion Matrix

- Classification Report

(Random Forest provided strong performance on this dataset.)

## 🧪 How It Works

- User enters customer details in the web app

- Input data is scaled using the saved scaler

- Trained model predicts churn

- Result is displayed instantly

## 🔮 Future Improvements

- Add model comparison in the web app

- Deploy on cloud (Streamlit Cloud)

- Improve UI design

- Add probability-based predictions

- Support batch predictions via CSV upload

## 👨‍💻 Author

Shreya Dalvi  

Machine Learning & Data Science Project
