# ANN Classification – Customer Churn Prediction

This project is an end-to-end **ANN-based** customer churn prediction system with an interactive web application built using Streamlit. [web:31][web:26] The model predicts whether a customer is likely to leave the service (churn) based on their profile and activity features. [web:31]

🔗 **Live App:** https://annclassificationcustomerchurnprediction.streamlit.app/  
📂 **Tech Stack:** Python, Pandas, NumPy, Scikit-learn, TensorFlow/Keras, Streamlit [web:31][web:29]

---

## Project Overview

Customer churn prediction helps businesses identify customers who are likely to discontinue their services so that they can take proactive retention actions. [web:25][web:29]  
This project implements an Artificial Neural Network (ANN) classification model to predict churn using structured customer data (e.g., credit score, geography, gender, age, balance, tenure, etc.). [web:29][web:31]

Key capabilities:
- ANN model for binary classification (Churn vs No Churn). [web:31]
- Preprocessing pipeline for encoding categorical variables and scaling numerical features. [web:28][web:31]
- Streamlit web app for user-friendly, real-time predictions. [web:29][web:25]

---

## Dataset

The project uses a typical bank customer churn dataset similar to `Churn_Modelling.csv`, containing the following types of features: [web:29][web:28]

- CustomerID, Surname  
- CreditScore, Age, Tenure, Balance  
- Geography, Gender  
- NumOfProducts, HasCrCard, IsActiveMember  
- EstimatedSalary  
- Target variable: **Exited** (1 = churned, 0 = not churned)

You can replace this with your own churn dataset as long as you adapt the preprocessing code accordingly. [web:25]

---

## Project Structure

A typical structure for this project is: [web:29][web:31]

```text
ANN_Classification_Customer_Churn_Prediction/
├─ data/
│  └─ Churn_Modelling.csv
├─ models/
│  ├─ ann_model.h5
│  ├─ scaler.pkl
│  └─ encoder.pkl
├─ app.py                 # Streamlit app
├─ training_notebook.ipynb
├─ requirements.txt
└─ README.md
