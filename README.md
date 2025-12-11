# 📉 Customer Churn Analysis

This project provides a clear and simple analysis of telecom customer churn.
I explored contract types, monthly charges, tenure, service usage, and payment methods to understand why customers leave.
The goal is to identify churn patterns and provide actionable insights for customer retention.

---

## 📌 What This Project Covers

- Loaded and cleaned the churn dataset
- Converted numeric + categorical colmns
- Handled missing values in TotalCharges
- Exploratory Data Analysis (EDA)
- Visual insights on churn behavior
- Identified churn-driving factors
- Provided business recommendations

Tools used: Pandas, NumPy, Matplotlib, Seaborn

---

## 📂 Folder Structure
Customer-Churn-Analysis/  
│── data/  
│   └── Telco_Customer_Churn.csv  
│── images/  
│   ├── churn_count.png  
│   ├── monthly_charges_dist.png  
│   ├── tenure_vs_churn.png  
│   ├── monthly_charges_vs_churn.png  
│   └── correlation_heatmap.png  
│── notebooks/  
│   └── churn_analysis.ipynb  
│── README.md  

---

## 📊 Key Insights

- Customers on Month-to-Month contracts churn the most.
- Higher Monthly Charges strongly relate to churn.
- Customers with low tenure (0–6 months) churn frequently.
- Customers using Electronic Check payment method churn more.
- Senior citizens show a higher churn rate compared to younger customers.

---
  
## 📈 Visual Highlights

- The notebook includes visualizations such as:
- Churn distribution
- Monthly charges distribution
- Tenure vs churn
- Monthly charges vs churn
- Correlation heatmap
- These visuals help identify which features contribute to churn the most.

---

## 🚀 How to Run This Project

1. Clone the repository.
2. Open /notebooks/churn_analysis.ipynb in Jupyter Notebook.
3. Install required libraries:
`pip install pandas numpy matplotlib seaborn`
4. Run all cells to explore churn insights and visualizations.

---

## 🙋‍♂️ Author

Ayush Saini  
Aspiring Data Analyst  
📧 Email: ayushsaini8535@gmail.com  
