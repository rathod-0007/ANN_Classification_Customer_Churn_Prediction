# 📉 ANN Customer Churn Prediction

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://annclassificationcustomerchurnprediction.streamlit.app/)
![Python](https://img.shields.io/badge/Python-3.11%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.0%2B-orange)
![License](https://img.shields.io/badge/License-MIT-green)

A machine learning web application that predicts customer churn probability using an **Artificial Neural Network (ANN)**. Built with **TensorFlow/Keras** for the backend model and **Streamlit** for the frontend interface.

🔗 **Live Demo:** [Click Here to View App](https://annclassificationcustomerchurnprediction.streamlit.app/)

---

## 📌 Project Overview

Customer churn refers to the phenomenon where customers stop doing business with a company. This project assists businesses in identifying at-risk customers by analyzing demographic and behavioral data.

The application takes user inputs (such as credit score, geography, gender, age, balance, etc.), processes the data using a pre-trained ANN model, and outputs a prediction:
* **Exited (1):** The customer is likely to churn.
* **Stayed (0):** The customer is likely to stay.

---

## 🚀 Features

* **Deep Learning Model:** Utilizes a multi-layer Artificial Neural Network built with TensorFlow.
* **Data Preprocessing:** Handles One-Hot Encoding for categorical variables (Geography, Gender) and Feature Scaling for numerical data.
* **Interactive UI:** User-friendly form inputs via Streamlit.
* **Real-time Prediction:** Instant classification with probability scores.

---

## 🛠️ Tech Stack

| Component | Tools Used |
| :--- | :--- |
| **Language** | Python |
| **Deep Learning** | TensorFlow, Keras |
| **Data Manipulation** | Pandas, NumPy |
| **Machine Learning** | Scikit-Learn (Preprocessing, Split) |
| **Web Framework** | Streamlit |
| **Model Serialization** | Pickle |

---

## 📂 Repository Structure

```text
├── .streamlit/             # Streamlit configuration
├── model/
│   ├── model.h5            # Saved ANN model (Keras format)
│   ├── label_encoder_gender.pkl
│   ├── onehot_encoder_geo.pkl
│   └── scaler.pkl          # StandardScaler object
├── app.py                  # Main Streamlit application
├── prediction.py           # Prediction logic helper
├── requirements.txt        # Project dependencies
└── README.md               # Documentation
