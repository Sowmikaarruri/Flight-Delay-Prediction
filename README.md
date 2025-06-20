# Flight-Delay-Prediction
This project predicts flight delays using a deep learning model trained on U.S. domestic flight data. Built with TensorFlow/Keras, the model classifies flights as "On Time" or "Delayed" based on features like departure time, flight number, and schedule. The project includes a Streamlit-based web application 
# ✈️ Flight Delay Prediction using Deep Learning

This project predicts whether a flight will be delayed based on historical flight data using deep learning. It includes an interactive Streamlit web application where users can register, log in, and check delay predictions for their reserved flights.

---

## 📌 Project Overview

Flight delays are a common inconvenience for travelers. This project utilizes a deep learning approach to predict delays based on a variety of features from a real-world dataset. It also includes a web-based user interface for interactive use.

---

## 📊 Dataset

Source: [Kaggle - U.S. Flight Delays](https://www.kaggle.com/datasets/usdot/flight-delays?select=flights.csv)  
Used fields: flight number, departure time, arrival time, date, etc.

A processed subset of the dataset is included as `trialF.csv`.

---

## 🧠 Model Overview

- **Architecture:** LSTM Neural Network
- **Framework:** TensorFlow / Keras
- **Output:** Binary classification (`Delayed` or `On Time`)
- **Training Code:** Implemented in `Flights.ipynb`
- **Weights File:** `lstm_model_weights.weights.h5`

---

## 🚀 Web Application (Streamlit)

### 🛠️ Features:
- User login and registration
- User profile page
- Flight delay predictions based on reserved or entered flight number
- Visual UI with a background image and styled layout

---

## ▶️ How to Run the App

### 1. Setup
Make sure the following files are in the same directory:
- `flights_app.py`
- `trialF.csv`
- (Optional) `lstm_model_weights.weights.h5` if retraining or using model logic

### 2. Install Streamlit
```bash
pip install streamlit
