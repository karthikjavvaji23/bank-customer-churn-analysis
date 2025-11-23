# 🔵 **Bank Customer Churn Analysis & Prediction**

An end-to-end analytics project combining **Python, Machine Learning, and Power BI** to understand why customers leave a bank and to predict which customers are most likely to churn. This project demonstrates strong skills in **data analysis, BI reporting, feature engineering, and business interpretation**.
<img width="1289" height="729" alt="Screenshot 2025-11-23 132441" src="https://github.com/user-attachments/assets/16e4f8a2-673d-41dd-ac81-2d7b1182f427" />

---

## 🏦 **Project Overview**

This project analyzes a banking dataset to identify patterns that lead to customer churn.
I cleaned and prepared the data, explored customer behavior, built a **Random Forest** prediction model, generated a **churn risk score**, and designed a **Power BI dashboard** that visualizes the insights for business users.

This workflow reflects a real-world business analytics pipeline from raw data → insights → prediction → decision support.

---

## 🎯 **Key Business Questions**

* What is the bank’s churn rate?
* Which countries, age groups, and customer segments churn the most?
* How does activity level, tenure, credit score, and number of products affect churn?
* Which features contribute most to churn?
* Which customers are at highest risk and should be prioritized for retention?

---

## 💡 **Main Insights**

* **Germany has the highest churn (~32%)**, indicating a regional retention issue.
* **Inactive customers churn nearly twice as much** as active members.
* Churn is **highest among ages 45–55**, pointing to mid-life financial shifts.
* Customers with **low tenure (0–3 years)** leave more frequently.
* Customers with **only one product** are significantly more churn-prone.

These insights help the bank focus on engagement, early onboarding, and product cross-selling.

---

## 🧠 **Machine Learning Model**

* **Model:** Random Forest Classifier
* **Accuracy:** ~80%
* **AUC:** ~0.74
* **Output:** A “churn_risk_score” between 0–1 for each customer
* **Most important factors:** Age, Tenure, Activity Level, Balance, Geography

The churn risk score was integrated into the Power BI dashboard for customer-level decision-making.

---

## 📊 **Power BI Dashboard**

The dashboard includes 3 pages:

### **1️⃣ Executive Summary**

* Total customers, churn count, churn rate
* Churn by geography
* Churn by age (with max/min highlights)
* Active vs inactive churn comparison

### **2️⃣ Customer Segmentation**

* Age groups
* Tenure bands
* Product count vs churn
* Balance & salary distribution

### **3️⃣ Prediction & Strategy**

* Churn risk distribution
* High-risk customer list
* Model feature importance
* Recommended retention actions

---

## 📂 **Repository Structure**

```
data/
notebooks/
dashboards/
images/
reports/
README.md
```

---

## 🧰 **Tools & Technologies**

* **Python:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
* **Power BI:** DAX, data modeling, interactive reporting
* **Version Control:** Git & GitHub

---

## 👤 **Author**

**Karthik Javvaji**
Data Analyst | BI Developer | ML Enthusiast
📧 [karthikjavvaji18@gmail.com](mailto:karthikjavvaji18@gmail.com)
