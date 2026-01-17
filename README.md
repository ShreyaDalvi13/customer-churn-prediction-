📉 Customer Churn Prediction Web App

This project is a Customer Churn Prediction System that uses Machine Learning to predict whether a customer is likely to leave a telecom service. The model is deployed as an interactive web application using Streamlit.
Link : http://localhost:8501/

🚀 Features

Predicts customer churn (Yes/No) based on input features

Trained using Machine Learning algorithms

User-friendly Streamlit web interface

Pre-trained model and scaler for fast predictions

Real-world Telco Customer Churn dataset

🧠 Machine Learning Models Used

Logistic Regression

Random Forest Classifier

StandardScaler for feature scaling

Model training and evaluation are performed in the Jupyter Notebook.

🗂️ Project Structure
📁 Customer-Churn-Prediction
│
├── churn prediction code.ipynb   # Model training & evaluation
├── churn_model.pkl               # Trained ML model
├── scaler.pkl                    # Feature scaler
├── WA_Fn-UseC_-Telco-Customer-Churn.csv  # Dataset
├── app.py                        # Streamlit web app
├── README.md                     # Project documentation

📊 Dataset

Source: Telco Customer Churn Dataset

Format: CSV

Target Variable: Churn (Yes / No)

The dataset includes customer details such as:

Demographics

Account information

Services subscribed

Billing details

🖥️ Web Application

The application is built using Streamlit and runs locally.

Run the App Locally
streamlit run app.py


Then open your browser and go to:

http://localhost:8501/

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/customer-churn-prediction.git
cd customer-churn-prediction

2️⃣ Install Required Libraries
pip install -r requirements.txt


Main Libraries Used:

pandas

numpy

scikit-learn

matplotlib

seaborn

streamlit

pickle

📈 Model Performance

The model is evaluated using:

Accuracy Score

Confusion Matrix

Classification Report

(Random Forest provided strong performance on this dataset.)

🧪 How It Works

User enters customer details in the web app

Input data is scaled using the saved scaler

Trained model predicts churn

Result is displayed instantly

🔮 Future Improvements

Add model comparison in the web app

Deploy on cloud (Streamlit Cloud / Render / AWS)

Improve UI design

Add probability-based predictions

Support batch predictions via CSV upload

👨‍💻 Author

shreya dalvi
Machine Learning & Data Science Project

📜 License

This project is for educational purposes.
