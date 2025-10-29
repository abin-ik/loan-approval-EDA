# 🏦 Loan Approval EDA Project

This project performs **Exploratory Data Analysis (EDA)** on a loan dataset to understand the key factors that influence loan approval decisions.  
The analysis focuses on applicant income, credit score, years employed, loan amount, and derived point scores.

---

## 📊 Objective

The goal of this analysis is to identify patterns and thresholds that determine **loan approval** based on the dataset.

---

## 🔍 Key Questions & Analysis

### 1️⃣ How much income is needed to get the loan approved?
- **Observation:** Applicants with an income of around **₹1,00,000 or more** have a higher chance of loan approval.  
- **Insight:** Income positively contributes to the loan approval points.

---

### 2️⃣ What is the minimum credit score required for approval?
- **Observation:** A **credit score of 600 or above** is generally required for loan approval.  
- **Insight:** Credit score has a strong positive influence on the approval outcome.

---

### 3️⃣ Does years employed affect loan approval?
- **Observation:** **Years employed** does not directly affect the loan approval status.  
- **Insight:** While longer employment adds minor points, it is not a deciding factor.

---

### 4️⃣ What is the relationship between calculated points and loan approval?
- **Formula Used:points = 0.0003*income + 0.05*(credit_score/10) + 0.5*years_employed - 0.001*loan_amount; loan_approved = points >= 65
**
