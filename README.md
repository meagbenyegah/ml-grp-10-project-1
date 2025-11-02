# 🎓 CSCD613 - Machine Learning with Big Data Analytics (Group 10)
## 🧩 Project 1: Loan Default Prediction using Machine Learning

---

## 🗂️ Dataset download
Download the dataset from the following Google Drive link and place the downloaded file(s) into the `data/` folder in this repository (the repository is configured to ignore large files in `data/`):

https://drive.google.com/drive/folders/1JkAmwegoXL_kXKeITShG_hSSehfyZaqi?usp=share_link

---

## 📘 Overview
This project uses **machine learning** techniques to predict whether a loan applicant is likely to **default** on a loan based on their demographic, financial, and socioeconomic information.  
The analysis is based on the **Home Credit Default Risk dataset** from [Kaggle](https://www.kaggle.com/competitions/home-credit-default-risk/data).

Accurate loan default prediction models can help financial institutions and microfinance firms — especially in countries like **Ghana** — to minimize credit risk, improve lending decisions, and promote financial inclusion.

---

## 🎯 Objectives
- Build and evaluate a predictive model that classifies loan applicants as **defaulters (1)** or **non-defaulters (0)**.  
- Identify key features influencing loan repayment behavior.  
- Demonstrate how data-driven approaches can improve **credit risk assessment** in financial institutions.

---

## 🧠 Machine Learning Approach

````markdown
# 🎓 CSCD613 - Machine Learning with Big Data Analytics (Group 10)
## 🧩 Project 1: Loan Default Prediction using Machine Learning

---

Example (manual):
1. Download the file from the link above (you may need to sign in to Google).
2. Move or copy the downloaded `application_train.csv` into the project's `data/` directory so the pipeline can find it.

---

## 📘 Overview
This project uses **machine learning** techniques to predict whether a loan applicant is likely to **default** on a loan based on their demographic, financial, and socioeconomic information.  
The analysis is based on the **Home Credit Default Risk dataset** from [Kaggle](https://www.kaggle.com/competitions/home-credit-default-risk/data).

Accurate loan default prediction models can help financial institutions and microfinance firms — especially in countries like **Ghana** — to minimize credit risk, improve lending decisions, and promote financial inclusion.

---

## 🎯 Objectives
- Build and evaluate a predictive model that classifies loan applicants as **defaulters (1)** or **non-defaulters (0)**.  
- Identify key features influencing loan repayment behavior.  
- Demonstrate how data-driven approaches can improve **credit risk assessment** in financial institutions.

---

## 🧠 Machine Learning Approach

| Step | Description |
|------|--------------|
| **1. Data Collection** | Dataset obtained from Kaggle: *Home Credit Default Risk* |
| **2. Data Cleaning** | Handle missing values, encode categorical variables, fix outliers, and normalize features |
| **3. Feature Engineering** | Derived ratios like credit-to-income and annuity-to-income |
| **4. Model Training** | Algorithms tested: Logistic Regression, Random Forest, XGBoost |
| **5. Evaluation Metrics** | Accuracy, Precision, Recall, F1-score, ROC-AUC |
| **6. Interpretation** | Feature importance and correlation analysis |

---

## 📊 Dataset Information
**File used:** `application_train.csv`  
**Rows:** ~300,000  
**Columns:** ~120  

**Target variable:**  
- `TARGET`: 1 → Loan defaulted  
- `TARGET`: 0 → Loan repaid successfully  

**Example features:**
- `AMT_INCOME_TOTAL`: Applicant’s total income  
- `AMT_CREDIT`: Credit amount requested  
- `DAYS_BIRTH`: Age (in negative days)  
- `NAME_EDUCATION_TYPE`: Level of education  
- `CODE_GENDER`: Gender of applicant  
- `CNT_CHILDREN`: Number of dependents  

---

## ⚙️ Installation & Requirements
You can run this project using **Python 3.8+**.  
Install the required libraries using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```
````