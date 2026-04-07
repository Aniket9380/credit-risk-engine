# credit-risk-engine
Developed an end-to-end AI Credit Risk Engine leveraging Python, PySpark, and Databricks to predict Probability of Default (PD), calculate Expected Loss, and generate automated credit decisions. Implemented multi-layer Pareto analysis to identify high-risk customer segments contributing to majority portfolio risk.



# 💳 AI Credit Risk Engine with Risk-Layer Pareto Analysis

---

## 🚀 Project Overview

This project presents an end-to-end **AI-driven Credit Risk Analytics Engine** designed to predict the likelihood of loan default and support data-driven credit decisioning.

The system leverages machine learning techniques to estimate **Probability of Default (PD)** and extends beyond traditional modeling by incorporating **Expected Loss (EL)** and **Risk-layer Pareto analysis** to identify high-risk customer segments contributing disproportionately to portfolio risk.

---

## 🎯 Objectives

* Predict **Probability of Default (PD)** for loan applicants
* Enable **risk-based decisioning** (Approve / Review / Reject)
* Quantify **financial risk using Expected Loss (EL)**
* Identify **high-risk segments using Pareto analysis (80/20 rule)**
* Build an **interactive analytics system** for credit risk insights

---

## 🧠 Key Features

### 🔹 1. Credit Risk Modeling

* Built a machine learning model to estimate PD
* Used customer demographics, financial attributes, and loan characteristics
* Generated risk scores for decision-making

---

### 🔹 2. Risk-Based Decision Engine

* PD < 0.2 → ✅ Approve
* 0.2 ≤ PD < 0.5 → ⚠️ Review
* PD ≥ 0.5 → ❌ Reject

---

### 🔹 3. Expected Loss (EL) Calculation

Expected Loss is calculated using:

EL = PD × LGD × EAD

Where:

* **PD** → Probability of Default
* **LGD** → Loss Given Default (assumed 50%)
* **EAD** → Exposure at Default (loan amount)

---

### 🔹 4. Risk-Layer Pareto Analysis

#### ✅ Layer 1: Risk Score Pareto

* Identifies top customers contributing most to total risk


### 🔹 5. Feature Engineering

* Income-to-loan ratio
* Risk ratio (interest × income %)
* Customer segmentation (income buckets)


## 📊 Dataset Description

The dataset includes:

### Customer Features

* Age
* Income
* Employment Length

### Loan Features

* Loan Amount
* Interest Rate
* Loan Intent
* Loan Grade

### Credit Behavior

* Credit History Length
* Previous Defaults

### Model Outputs

* Probability of Default (PD)
* Risk Score
* Decision


## 📈 Sample Output

| Age | Income | Loan Amount | PD   | Decision |
| --- | ------ | ----------- | ---- | -------- |
| 25  | 50000  | 20000       | 0.12 | Approve  |
| 40  | 30000  | 50000       | 0.65 | Reject   |

---

## 📊 Key Insights

* Top 20–30% of customers contribute to majority of portfolio risk
* Expected Loss provides better financial risk estimation than PD alone
* Lower income segments show higher risk concentration
* Model effectively separates high-risk vs low-risk applicants

---

## 🏆 Business Impact

* Improves credit approval decision-making
* Reduces financial losses through risk identification
* Enables targeted risk mitigation strategies
* Supports data-driven lending policies

---

## 👨‍💻 Author

**Aniket Singh**
Data Analyst | Aspiring Data Scientist

