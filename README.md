🌲🔥 Fire Weather Index (FWI) Prediction – Streamlit App

This project is a Machine Learning–based Fire Weather Index (FWI) prediction system built using a Random Forest model, supported by data preprocessing with a trained scaler, and deployed using Streamlit.
The system predicts the Fire Weather Index using weather-related input features, helping detect wildfire risk early and support environmental safety measures.

🚀 Project Overview

The project provides a simple and interactive UI where users can enter weather parameters such as temperature, humidity, wind speed, and more.
The backend ML model processes these values and returns a predicted FWI score, which indicates potential fire danger levels.

This tool is ideal for:

Forest departments

Environmental researchers

Safety planners

Students learning ML deployment

🧠 Features
✔ Machine Learning Model (Random Forest)

Predicts Fire Weather Index with good accuracy

Trained on real-world FWI/weather datasets

✔ Preprocessing Included

scaler_fwi.pkl is used to scale inputs to match training distribution

Ensures accurate predictions

✔ Streamlit Web Application

Clean and interactive UI

Runs locally or deployable on Streamlit Cloud

✔ Modular & Organized Project

Separate folders and files for app, models, and requirements

Easy to understand and extend

📁 Project Structure
streamlit-fwi/
│── app/
│   └── app.py                # Streamlit UI and prediction logic
│── random_forest_fwi_model.pkl
│── scaler_fwi.pkl
│── requirements.txt
│── .gitignore
│── README.md

🧩 Tech Stack
Frontend & Deployment

Streamlit

Machine Learning

Random Forest Regressor (scikit-learn)

StandardScaler (for preprocessing)

Languages

Python 3.x
📊 How the App Works

User inputs weather conditions

Streamlit sends the values to the ML model

Inputs are scaled using scaler_fwi.pkl

Model predicts the Fire Weather Index

App displays the predicted FWI value and danger level

🔥 Example Output

FWI Score: 23.7

Danger Level: 🔴 High Fire Risk
