# Machine_Project
A Flask web app that predicts whether a job has a high salary based on user input.
# Salary Predictor Web App

This is a machine learning web application built with **Flask** that predicts whether a job offers a high salary based on input features such as company rating, founding year, seniority, location, and average salary.

## 🔍 Features

- Web interface for user input (Flask + HTML)
- Machine learning model (trained on job dataset)
- Feature selection using `SelectKBest`
- Classification using Logistic Regression / Random Forest / SVC
- Live prediction based on user form

## 📊 Input Fields

- `Rating` (e.g., 4.2)
- `Founded` (e.g., 2010)
- `Seniority` (e.g., Junior, Senior)
- `State` (e.g., CA, TX)
- `Average Salary` (numeric)

## 🧠 Machine Learning Pipeline

- Cleaned dataset using Pandas
- Feature encoding with `pd.get_dummies()`
- Feature selection via `SelectKBest` + `f_classif`
- Model training with classification algorithms
- Model + feature columns saved using `joblib`

- ## 🗃️ Files

- `app.py` — Flask server
- `model.pkl` — Trained model
- `features.pkl` — List of encoded feature names
- `templates/index.html` — HTML form UI
- `README.md` — Project documentation
