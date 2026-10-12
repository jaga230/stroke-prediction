# 🏥 Clinical Decision Support System for Stroke Prediction

📔 *End-to-End Machine Learning Project | Healthcare + Predictive Analytics*

<p align="left">
  <img src="[https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)" />
  <img src="[https://img.shields.io/badge/Machine%20Learning-F7931E?style=flat-square&logo=scikit-learn&logoColor=white](https://img.shields.io/badge/Machine%20Learning-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)" />
  <img src="[https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)" />
  <img src="[https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)" />
  <img src="[https://img.shields.io/badge/Status-Completed-success?style=flat-square](https://img.shields.io/badge/Status-Completed-success?style=flat-square)" />
</p>

---

## 🚀 Summary

Developed a complete **machine learning pipeline and full-stack web application** to analyze patient biometrics and predict the probability of a stroke event. 

The project integrates **Scikit-Learn classification models** and delivers actionable medical insights through a **React.js clinical dashboard**, complete with automated emergency email triage and database logging.

---

## 📌 Project Overview

This project combines:
* 🫀 **Patient Biometrics** (Age, BMI, Average Glucose Level)
* 📋 **Medical History** (Hypertension, Heart Disease Status)
* ⚙️ **Clinical Override Logic** (Human-in-the-Loop MLOps)

👉 Objective: Understand how physiological factors impact **stroke risk** and provide medical professionals with an automated, high-speed triage tool.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
| :--- | :--- |
| 🐍 Python (Pandas/NumPy) | Data Cleaning & Transformation |
| 🤖 Scikit-Learn (SMOTE) | Model Training & Class Balancing |
| ⚡ Flask & REST API | Backend Server & Model Inference |
| ⚛️ React.js & Recharts | Dashboard UI & Longitudinal Visuals |
| 🍃 MongoDB Atlas | Patient Database & Triage Logging |
| 💻 VS Code | Development Environment |

---

## 📁 Project Structure

```text
stroke-prediction-system/
├── backend/                  # Python & Machine Learning
│   ├── healthcare-dataset.csv
│   ├── train.py             
│   ├── app.py               
│   └── stroke_model.pkl     
└── frontend/                 # React User Interface
    ├── package.json
    └── src/
        ├── App.js           
        └── components/
            └── PredictionForm.js

