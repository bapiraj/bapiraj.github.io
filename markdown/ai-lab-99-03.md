---
title: "Auto Insurance Premium Prediction using Multiple Linear Regression with Binary Data Preprocessing"
description: "A project to predict auto insurance premium amounts using age and accident history, applying binary encoding and Multiple Linear Regression."
datePublished: "2025-09-01"
dateModified: "2025-09-01"
---

# 🚗 Auto Insurance Premium Prediction (Multiple Linear Regression with Binary Data Preprocessing)

This project demonstrates a **Multiple Linear Regression** model to predict the insurance premium amount for an individual based on age and accident history in the past two years.  
It includes the full workflow from data loading and preprocessing to model training, interpretation, evaluation, and deployment via a Streamlit app.

---

## 📖 Project Description

- **Objective:** Predict the premium amount for auto insurance  
- **Model Used:** Multiple Linear Regression
- **Dataset:** A synthetic dataset of age, accident history, and insurance premiums  
- **Feature Preprocessing:**  
  - Applied binary encoding: accident history (Yes/No) → (1/0)  
- **Workflow:**  
  1. Data Loading  
  2. Data Exploration & Preprocessing  
  3. Model Selection & Training  
  4. Model Interpretation  
  5. Model Evaluation  
  6. Model Deployment  

---

## ⚙️ Setup

Clone the repository and install the required dependencies:

```bash
git clone https://github.com/bapiraj/ai-lab-99.git
cd 03_auto_insurance_premium_prediction
pip install -r requirements.txt
```

[Jupyter Notebook](https://github.com/bapiraj/ai-lab-99/blob/main/03_auto_insurance_premium_prediction/auto_insurance_prediction.ipynb)


Run the streamlit app
```bash
streamlit run app.py
```