# Customer Churn Analysis — Telco CRM Insights
**Author: Namrata Pote** | Business Analyst & Data Science Enthusiast  
🔗 [LinkedIn](https://linkedin.com/in/namrata-pote) | 📧 potenamrata456@gmail.com

---

## 📌 Project Overview
This project analyzes customer churn behavior for a telecom company 
using Exploratory Data Analysis (EDA) and Machine Learning classification 
models. As a Business Analyst, the goal is not just to build models — 
but to extract actionable CRM insights that help retain customers.

---

## 🎯 Business Problem
Customer churn directly impacts revenue. Retaining an existing customer 
is 5x cheaper than acquiring a new one. This analysis identifies:
- **Who** is likely to churn?
- **Why** are they churning?
- **What** can the CRM/business team do to retain them?

---

## 📊 Dataset
- Source: [Kaggle — Telco Customer Churn](https://www.kaggle.com/blastchar/telco-customer-churn)
- 7,043 customers | 21 features | Binary target: Churn (Yes/No)

---

## 🔍 Models Used
| Model | Accuracy |
|---|---|
| Logistic Regression | ~80% |
| Decision Tree | ~78% |
| Random Forest + Bagging | ~82% |
| KNN | ~76% |

---

## 💡 Key Business Insights (BA Perspective)
- Customers on **month-to-month contracts** churn 3x more than annual contracts
- **High monthly charges** + short tenure = highest churn risk
- Customers without **tech support or online security** churn more
- **Senior citizens** have higher churn rate despite lower volume

## ✅ CRM Recommendations
1. Offer contract upgrade incentives to month-to-month customers
2. Flag high-charge + low-tenure customers in CRM for proactive outreach
3. Bundle tech support with onboarding for new customers
4. Create targeted retention campaigns for senior citizen segment

---

## 🛠️ Tools & Skills
`Python` `Pandas` `Scikit-learn` `Matplotlib` `Seaborn` `Jupyter Notebook`

---

## 📁 Repository Structure
- `EDA.ipynb` — Exploratory Data Analysis
- `log_regression.ipynb` — Logistic Regression Model
- `decision_tree.ipynb` — Decision Tree Model
- `rf_bagging.ipynb` — Random Forest & Bagging
- `KNN.ipynb` — K-Nearest Neighbors
- `telco_churn_presentation.pdf` — Business Insights Presentation
