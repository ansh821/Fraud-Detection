Fraud Detection Model

This repository contains a Fraud Detection Model implemented in Python using Machine Learning techniques. The project demonstrates how to preprocess data, train models, and evaluate their performance in detecting fraudulent transactions.
A machine learning project that predicts whether a customer is likely to Fraud  on credit payment based on their financial information. The project includes data preprocessing, exploratory data analysis (EDA), model training, evaluation, and an interactive Streamlit web application for real-time predictions.

📌 Project Overview

Financial institutions need to identify customers who are at risk of defaulting on credit payments. This project uses supervised machine learning algorithms to analyze customer information and predict whether a customer is likely to default.

The notebook has been organized into a structured machine learning workflow for better readability, maintainability, and understanding.

 ✨ Features

- Clean and organized Jupyter Notebook

- Exploratory Data Analysis (EDA)

- Data preprocessing and feature scaling

- Multiple machine learning models

- Model comparison and evaluation

- Best model selection

- Manual prediction using user inputs

- Interactive Streamlit web application

- Model and scaler saved using Joblib

 📂 Project Structure


Credit_Default_Prediction/
│
├── Fraud Detection Model.ipynb      # Complete ML workflow
├── app.py                           # Streamlit application
├── fraud_detection_model.pkl        # Trained model
├── scaler.pkl                       # Feature scaler
├── Default.xlsx                     # Dataset
├── requirements.txt                 # Required libraries
└── README.md

 📊 Dataset Features

The model uses the following input features:

| Feature | Description |
|----------|-------------|
| Student | Whether the customer is a student (Yes/No) |
| Balance | Outstanding account balance |
| Income | Annual income |

 🎯 Target Variable

- Fraud
  - Yes
  - No


⚙️ Machine Learning Workflow

1. Import Libraries
2. Load Dataset
3. Exploratory Data Analysis (EDA)
4. Data Preprocessing
5. Feature Scaling
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Best Model Selection
10. Save Model
11. Manual Prediction
12. Streamlit Deployment

 🤖 Machine Learning Models Used

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes
- Support Vector Machine (SVM)

The best-performing model is selected based on evaluation metrics.

 📈 Evaluation Metrics

The models are evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report
- Precision
- Recall
- F1 Score
- ROC-AUC Score (where applicable)

 🚀 Running the Streamlit Dashboard

## 1️⃣ Clone the Repository
Before running the file the dashboard file should be in .py format not in .ipynb format.
bash
git clone https://github.com/ansh821/Fraud-Detection
cd your-repository

2️⃣ Install Dependencies

bash
pip install -r requirements.txt

 3️⃣ Run the Application

bash
streamlit run dashboard.py

4️⃣ Open in Browser

Streamlit will automatically open in your browser.

If not, visit:

http://localhost:8501

💻 Using the Application

Enter the following customer details:

- Student Status (Yes/No)
- Account Balance
- Annual Income

Click Predict Fraud to receive:

- Default Prediction (Yes/No)
- Prediction Confidence
- Customer Information Summary



 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Streamlit
- Jupyter Notebook



 📸 Future Improvements

- Deploy on Streamlit Community Cloud
- Add feature importance visualization
- Batch prediction using CSV/Excel upload
- Enhanced dashboard UI
- SHAP explainability for model predictions


 👩‍💻 Author

**Anshika Chauhan**

- B.Tech CSE (AI & ML)
- Machine Learning & Data Science Enthusiast



📌 Use Case

Fraud detection is crucial for banks, fintech, and e-commerce platforms to minimize financial losses and detect suspicious transactions in real-time.

Run Online (Binder)
## 🚀 Launch in Binder
👉 [Click to Launch in Binder](https://mybinder.org/v2/gh/ansh821/Fraud-Detection.git/main?urlpath=%2Fdoc%2Ftree%2FFraud+Detection+Model.ipynb)

