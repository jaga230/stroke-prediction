# 🏥 Clinical Decision Support System for Stroke Prediction

📔 *End-to-End Machine Learning Project | Healthcare + Predictive Analytics*

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Machine%20Learning-F7931E?style=flat-square&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white" />
  <img src="https://img.shields.io/badge/Status-Completed-success?style=flat-square" />
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
stroke_prediction_cdss/
├── data/
│   ├── raw_stroke_data.csv
│   └── clean_stroke_data.csv
├── ml_pipeline/
│   ├── train_model.py
│   ├── stroke_model.pkl
│   └── scaler.pkl
├── backend/
│   ├── app.py
│   └── requirements.txt
└── frontend/
    ├── src/
    │   ├── App.js
    │   └── components/
    └── package.json
---
📸 Dashboard Preview
<img width="1482" height="906" alt="Screenshot 2026-10-11 173313" src="https://github.com/user-attachments/assets/eb08ad49-548e-4929-8f2d-538c29350385" />
🔍 Exploratory Data Analysis (EDA) & Modeling
Handling imbalanced medical data using SMOTE (Synthetic Minority Over-sampling Technique).

Feature scaling continuous variables (BMI, Glucose).

Training an ensemble Random Forest Classifier to capture non-linear biometric relationships.

Evaluating model precision and recall to minimize false negatives.

📈 Dashboard Features
Clinical Tools

Single-Patient Risk Assessment Form

Bulk CSV Batch Screening

PDF Medical Report Generation

Visuals & Analytics

AI Confidence Score gauges

High-Risk Patient Data Tables

Longitudinal Recharts tracking metrics over multiple visits

📉 Key Insights
🔴 Higher age and elevated average glucose levels are strongly associated with increased stroke risk.

⚖️ Addressing class imbalance with SMOTE significantly improved the model's ability to detect true positive stroke cases.

👨‍⚕️ Clinical override rules (e.g., automatically flagging extreme glucose levels regardless of ML probability) ensure patient safety.

🎯 Business & Clinical Impact
✔️ Identify high-risk patients instantly ✔️ Support public health decision-making ✔️ Enable automated emergency triage alerts ✔️ Improve hospital administrative workflows

🚀 How to Run
1. Install Backend Dependencies
Bash
cd backend
pip install flask flask-cors pandas scikit-learn
2. Run the Flask API Server
Bash
python app.py
3. Install & Run the Frontend
Bash
cd frontend
npm install
npm start
📌 Skills Demonstrated
Machine Learning Classification

Imbalanced Data Handling

RESTful API Development

Full-Stack Web Integration

State Management (React)

Data Storytelling

🏆 Project Highlights
End-to-end data science workflow

Multi-tier architecture (Client-Server-Database)

Real-world healthcare problem solving

Insight-driven medical dashboard

Clean and scalable folder structure

👨‍💻 Authors
Dalavai Vijay Jagan
