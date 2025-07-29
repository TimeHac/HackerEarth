# HackerEarth

# Shell.ai Hackathon – Sustainable Fuel Blend Property Prediction

## 📌 Overview
This repository contains my solution for the **Shell.ai Hackathon** hosted on HackerEarth. The challenge focused on predicting key blend properties of sustainable fuels using real-world scientific data. The objective was to develop a machine learning model that could generalize well on unseen blend compositions.

---

## 🎯 Problem Statement
Given a dataset containing various chemical and physical parameters of sustainable fuel blends, the goal was to:
- Build a regression model to predict specific fuel properties.
- Achieve high accuracy and generalization across different samples.
- Apply sound data science principles to handle domain-specific challenges.

---

## ⚙️ Approach

### 1. Data Preprocessing
- Handled missing and noisy data.
- Applied feature scaling and transformation techniques.
- Detected and treated outliers where necessary.

### 2. Feature Engineering
- Performed correlation analysis to reduce multicollinearity.
- Created derived features based on domain knowledge.

### 3. Modeling
- Evaluated multiple regression models:
  - CatBoost Regressor
  - XGBoost Regressor
  - Random Forest Regressor
- Used GridSearchCV for hyperparameter tuning.
- Employed cross-validation for robust performance estimation.

### 4. Evaluation
- Primary metric: Accuracy (custom evaluation as per competition)
- Additional metrics: MAE, RMSE for internal validation

---

## 📈 Results
- Final model achieved an **accuracy of 84.06%** on the competition dataset.
- Demonstrated strong generalization and stability during validation.

---

## 🧠 Key Learnings
- Tackled a regression problem with real-world industrial data.
- Explored advanced ensemble models and interpretability techniques.
- Improved understanding of applying ML in the sustainable energy domain.

---
## 🔗 Resources
- [Shell.ai Hackathon](https://www.hackerearth.com/challenges/hackathon/shell-ai-hackathon/) *(Hosted on HackerEarth)*
- [CatBoost Documentation](https://catboost.ai/)

---

## ⚠️ Disclaimer
*The dataset used in this project was provided by Shell.ai as part of the hackathon. It is proprietary and cannot be publicly shared.*

---

## 🤝 Contact
If you'd like to connect or collaborate on similar projects:
- 📧 Email: aashutoshyadav81205@gmail.com
- 💼 LinkedIn: [YourLinkedInProfile](https://www.linkedin.com/in/aashutosh-yadav-1a07352a5/)

---
