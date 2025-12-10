# Customer Churn Prediction with Machine Learning & SHAP

End-to-end machine learning project to predict customer churn on the Telco Customer Churn dataset.  
The goal is not only to build accurate models, but also to understand **why** customers churn using **SHAP** (Explainable AI).

---

##  Project Overview

**Main steps:**

1. Data loading & cleaning  
2. Exploratory Data Analysis (EDA)  
3. Preprocessing with `ColumnTransformer` (scaling + one-hot encoding)  
4. Model training & comparison  
   - Logistic Regression  
   - Random Forest  
   - XGBoost  
5. Model evaluation (classification metrics + ROC-AUC)  
6. Model explainability with **SHAP**  
   - Global feature importance  
   - Individual prediction explanations  

---

##  Dataset

- **Name:** Telco Customer Churn  
- **Source:** Kaggle (Telco Customer Churn dataset)  
- **Target variable:** `Churn` (0 = no churn, 1 = churn)

Main features used:

- `tenure`, `MonthlyCharges`, `TotalCharges`  
- Contract type, internet service, online security, tech support, payment method, etc.

---

##  Tech Stack

- **Language:** Python  
- **Libraries:**  
  - `pandas`, `numpy`  
  - `matplotlib`, `seaborn`  
  - `scikit-learn`  
  - `xgboost`  
  - `shap`  

---

## 📁 Project Structure

```bash
.
├── data/
│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── Main.ipynb                
├── README.md
├── requirements.txt           
└── .gitignore
└── environment.yml
