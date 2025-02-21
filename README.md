# Customer-Retention-EDA-
# 📊 Customer Churn Analysis - Exploratory Data Analysis (EDA)
## 📌 Overview
Customer churn is a major challenge for telecom companies, as losing customers directly affects revenue. This project focuses on **Exploratory Data Analysis (EDA)** to uncover insights about customer behavior, service preferences, and key factors influencing churn.

## 📂 Project Structure
📁 Customer-Churn-EDA
├── 📜 customerchurnEDA.ipynb (Exploratory Data Analysis notebook)
├── 📂 data/ (Dataset files, if applicable)
├── 📜 requirements.txt (Dependencies for running the project)
├── 📜 README.md (This documentation file)

---

## 📊 Dataset Information
- **Dataset**: [Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)
- **Rows**: 7,043 customers
- **Columns**: 21 features related to customer demographics, service subscriptions, and billing.
- **Target Variable**: `Churn` (Yes/No) → Indicates whether a customer churned.

### 🔹 Key Features:
- **Customer Demographics**: `gender`, `SeniorCitizen`, `Partner`, `Dependents`
- **Services Subscribed**: `InternetService`, `OnlineSecurity`, `StreamingTV`, etc.
- **Billing & Contract**: `MonthlyCharges`, `TotalCharges`, `Contract`, `PaymentMethod`
- **Churn Status**: `Churn` (Target Variable)

---

## 📊 Exploratory Data Analysis (EDA)
✔ **Step 1: Data Cleaning & Preprocessing**  
- Handle missing values  
- Convert categorical features into numerical  

✔ **Step 2: Understanding Customer Behavior**  
- Distribution of **Churn vs. Non-Churn** customers  
- Analysis of **Tenure, Monthly Charges, and Contract Types**  
- Identifying high-risk churn groups  

✔ **Step 3: Visualizing Key Insights**  
- **Bar charts & Pie charts** for categorical variables  
- **Histograms & Boxplots** for numerical variables  
- **Correlation heatmap** to understand feature relationships  

✔ **Step 4: Key Business Insights**  
- **Which factors influence customer churn the most?**  
- **What type of customers are most likely to leave?**  

---

## 🎯 Key Insights from EDA
📌 Customers with **month-to-month contracts** have the highest churn rate.  
📌 Higher **monthly charges** correlate with increased churn.  
📌 Customers with **fiber optic internet** have a higher churn rate compared to DSL users.  
📌 Lack of **tech support or online security services** increases the likelihood of churn.  

---

## 🚀 How to Run This Project
To run this project on your local machine, follow these steps:

### 1️⃣ **Clone the Repository**
```bash
git clone https://github.com/your-github-username/Customer-Churn-EDA.git
cd Customer-Churn-EDA
2️⃣ Set Up Virtual Environment (Optional but Recommended)
python -m venv churn_env
source churn_env/bin/activate  # Mac/Linux
churn_env\Scripts\activate     # Windows

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Run the Jupyter Notebook
jupyter notebook

Then, open customerchurnEDA.ipynb and run the cells.
