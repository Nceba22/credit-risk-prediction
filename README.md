# Credit Risk Prediction 
A machine learning project that predicts individual credit default risk using historical financial data. This project demonstrates end-to-end data processing, feature engineering, classification modeling, and performance evaluation to assist financial institutions in making informed lending decisions.

---

## 📌 Project Overview
Credit risk assessment is a critical function in commercial banking and peer-to-peer lending. The goal of this project is to build an automated classification pipeline to determine whether an applicant is creditworthy or poses a high risk of default based on key financial indicators.

### Key Objectives
* **Feature Engineering:** Extract meaningful metrics like Debt-to-Income (DTI) ratio, credit utilization rates, and payment history indices.
* **Model Training:** Implement baseline and ensemble classification algorithms (Logistic Regression, Decision Trees, Random Forest).
* **Imbalance Handling:** Manage class imbalances common in loan default datasets using stratified sampling and weighted metrics.
* **Evaluation:** Measure predictive performance using Precision, Recall, F1-Score, and ROC-AUC.

---

## 🛠️ Tech Stack & Tools
* **Language:** Python 3.9+
* **Environment:** Jupyter Notebook
* **Libraries:** 
  * Data Processing: `pandas`, `numpy`
  * Machine Learning: `scikit-learn`
  * Visualization: `matplotlib`, `seaborn` (optional)
* **Version Control:** Git & GitHub

---

## 📂 Project Structure
```text
credit-risk-prediction/
├── data/                  # Raw and processed datasets
├── notebooks/             # Jupyter notebooks for analysis and modeling
│   └── credit_risk_model.ipynb
├── src/                   # Source scripts (modularized helper functions)
├── .gitignore             # Git ignore rules
├── requirements.txt       # Dependencies
└── README.md              # Project documentation