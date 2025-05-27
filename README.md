
# 🧠 Project Early Turnaround

**Predicting NEET Risk Among UK Youth Using Machine Learning**

---

## 📌 Overview

Every year, thousands of young people in the UK become NEET — Not in Education, Employment or Training.  
But what if we could predict *who's at risk* — before it happens?

**Project Early Turnaround** is a solo data science project built to explore exactly that.

This case study uses a **realistically simulated dataset** to demonstrate how machine learning can help local councils, schools, and youth organisations proactively identify at-risk students.

---

## 🧾 Dataset

This project uses a synthetic dataset of **1,000 student profiles**, inspired by public UK education and social data trends.

Each student record includes:
- Academic performance (GCSE Maths & English)
- School attendance percentage
- SEN status, FSM eligibility, exclusions
- Household income
- Regional deprivation score
- Parent employment status

> ❗ **Note:** All data is simulated — no personal or sensitive records are used.

---

## ⚙️ Machine Learning Approach

We trained a **Random Forest Classifier** to predict a binary outcome:  
`NEET_Risk` = 1 if the student is likely to become NEET.

### Steps:
1. Data preprocessing & encoding
2. Train/test split (80/20)
3. Model training (Random Forest, 100 trees)
4. Performance evaluation (Confusion Matrix, Classification Report, ROC AUC)
5. Feature importance analysis

---

## 📈 Results

- **ROC AUC Score:** 0.98 ✅  
- **Top predictors:**  
  - Attendance  
  - GCSE results  
  - Household income  
  - Exclusions  
  - Regional deprivation

Visuals:
- [ROC Curve](./roc_curve_project_early_turnaround.png)
- [Feature Importance](./feature_importance_project_early_turnaround.png)

---

## 🔍 Key Takeaways

- Early school attendance patterns are highly predictive of NEET risk.
- Academic and socio-economic indicators compound risk.
- With real data, tools like this could power early interventions that change lives.

---

## 📌 How to Use

1. Clone the repo  
2. Open `project_early_turnaround.ipynb`  
3. Walk through each section with code, charts, and narrative

No installation required if running on Google Colab.

---

## 🧠 Who This Is For

- Education charities
- Local authorities
- Youth service providers
- Policy teams
- Data scientists interested in public impact

---

## ✅ Next Steps

- Collaborate with a local authority or academy trust to access real data
- Deploy a privacy-first pilot version
- Combine structured data with qualitative insights

---

## 📬 Get In Touch

Want help building a version of this for your organisation?  
**Let’s talk.** This project is built to start conversations and spark solutions.

