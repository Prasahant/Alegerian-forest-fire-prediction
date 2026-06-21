# 🌲🔥 Algerian Forest Fire Prediction (FWI Predictor)

## 📌 Project Overview

This project is a **Machine Learning web application** that predicts the **Fire Weather Index (FWI)** based on meteorological and environmental conditions. It helps estimate the likelihood and intensity of forest fires using real-world data from the Algerian Forest Fire dataset.

The model is deployed as a **Flask web application** and hosted on **Render**, providing real-time predictions through a simple and interactive UI.

---

## 🎯 Objective

The main objective of this project is to:
- Predict forest fire risk using environmental parameters
- Understand how weather conditions influence fire intensity
- Build an end-to-end Machine Learning deployment pipeline

---

## 🧠 Machine Learning Approach

- Algorithm Used: **Ridge Regression**
- Dataset: **Algerian Forest Fire Dataset**
- Steps involved:
  - Data Cleaning
  - Feature Engineering
  - Feature Scaling (StandardScaler)
  - Model Training
  - Model Evaluation
  - Deployment using Flask

---

## 📊 Input Features

The model takes the following inputs:

- 🌡 Temperature
- 💧 Relative Humidity
- 🌬 Wind Speed
- 🌧 Rainfall
- 🔥 FFMC (Fine Fuel Moisture Code)
- 📈 DMC (Duff Moisture Code)
- ⚡ ISI (Initial Spread Index)
- 🏷 Classes (Fire / No-Fire condition)
- 🌍 Region

---

## 🚀 Live Demo

👉 Deployed Application:  
https://alegerian-forest-fire-prediction.onrender.com

---

## 🧠 What I Learned in This Project

Through this project, I gained hands-on experience in end-to-end Machine Learning development:

### 📌 Ridge Regression
- Learned how Ridge Regression works by adding **L2 regularization** to reduce overfitting
- Understood how it handles **multicollinearity** between features
- Learned how tuning the **alpha parameter** affects model performance

### 📌 Regression Concepts
- Difference between **Linear Regression vs Ridge Regression**
- Importance of **bias-variance tradeoff**
- How regression models predict continuous values like FWI

### 📌 Machine Learning Workflow
- Data preprocessing and cleaning techniques
- Feature scaling using **StandardScaler**
- Model training and evaluation

### 📌 Deployment Skills
- Building Flask web applications
- Connecting ML models with frontend forms
- Deploying project on cloud using **Render**
- Handling production issues like dependency versions

---

## 🛠 Tech Stack

- Python 🐍
- Flask 🌐
- Scikit-learn 🤖
- Pandas 📊
- NumPy 🔢
- HTML5 & CSS3 🎨
- Render ☁️

---

## 📁 Project Structure
