# Credit-Card-Fraud-Detection-using-Machine-Learning

# 🚀 Machine Learning Web Applications (Flask + Python)

This repository contains two Machine Learning based web applications built using **Flask, Scikit-learn, TensorFlow, and Pandas**.

---

# 📌 Project 1: Fraud Transaction Detection System

🔹 **Main file:** `app.py`  
🔹 **Dataset:** `train_dataset.csv`  

## 📖 Overview

This project detects whether a financial transaction is **VALID** or **FRAUDULENT** using a trained deep learning model (`project_model.h5`).

### 🔎 Model Input Features

- Transaction date & time  
- Category  
- Card number  
- Date of birth (for age calculation)  
- Transaction amount  
- State  
- ZIP code  

### 🎯 Prediction Output

- ✅ VALID TRANSACTION  
- ❌ FRAUD TRANSACTION  

---

## 🛠 Tech Stack

- Python  
- Flask  
- TensorFlow / Keras  
- Scikit-learn  
- Pandas  
- NumPy  
- HTML Templates  

---

## ⚙️ Installation

```bash
# Clone repository
git clone https://github.com/your-username/your-repo-name.git

# Navigate into project folder
cd your-repo-name

# Create virtual environment (recommended)
python -m venv venv

# Activate virtual environment (Windows)
venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

▶️ How to Run (Fraud Detection App)
python app.py

Open in browser:
http://127.0.0.1:5000/

📂 Project Structure (Fraud Detection)
├── app.py
├── model/
│   └── project_model.h5
├── dataset/
│   └── train_dataset.csv
├── templates/
│   ├── index.html
│   ├── result.html
│   ├── upload.html
│   └── other HTML files

📌 Project 2: Text Classification / Crime Prediction System

🔹 Main file: app1.py
🔹 CSV Input File used in prediction

📖 Overview

This project performs text classification using:
CountVectorizer (NLP Feature Extraction)
Support Vector Machine (SVM)
Naive Bayes (alternative classifier option)

🔄 Workflow

Reads text data
Converts text into numerical features
Trains classifier
Predicts class label for user input text

🛠 Tech Stack

Python
Flask
Scikit-learn
Pandas
NLP (CountVectorizer)
SVM Classifier

▶️ How to Run (Text Classification App)
python app1.py

Open in browser:
http://127.0.0.1:5000/

📦 Required Libraries
Create a requirements.txt file with:

flask
numpy
pandas
scikit-learn
tensorflow
joblib

Install using:
pip install -r requirements.txt

💡 Features

✅ Web Interface for Predictions
✅ File Upload & Preview
✅ Machine Learning Integration
✅ Deep Learning (Fraud Detection)
✅ NLP Text Classification

🔐 Future Improvements

Add authentication system
Deploy to Render / Railway / Heroku
Add database integration
Improve UI with Bootstrap
Add model performance metrics display

GitHub Project Structure

ml-web-app/
│
├── app/
│   ├── __init__.py
│   ├── routes.py
│   ├── utils.py
│   │
│   ├── templates/
│   │   ├── base.html
│   │   ├── first.html
│   │   ├── login.html
│   │   ├── home.html
│   │   ├── upload.html
│   │   ├── preview.html
│   │   ├── result.html
│   │   └── chart.html
│   │
│   └── static/
│       ├── css/
│       ├── js/
│       └── images/
│
├── models/
│   ├── project_model.h5
│   └── saved_model.pkl
│
├── data/
│   ├── train_dataset.csv
│   ├── upload.csv
│   └── upload.xlsx
│
├── notebooks/              # Optional (for experimentation)
│
├── tests/                  # Optional (future testing)
│
├── config.py
├── run.py
├── requirements.txt
├── .gitignore
└── README.md

👨‍💻 Author

Chellappa Herlan Pio
B.Sc Computer Science Graduate
Aspiring Java Full Stack Developer & ML Enthusiast
