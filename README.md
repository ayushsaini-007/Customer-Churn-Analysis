# 📉 Customer Churn Analysis

This project is a clear and simple analysis of telecom customer data.  
I explored contract types, monthly charges, tenure, and service usage to understand why customers leave (churn).  
The main goal is to identify patterns behind customer churn and provide recommendations to help improve retention.

---

## 📌 What This Project Covers

- Loaded and cleaned the churn dataset  
- Converted TotalCharges to numeric  
- Removed missing and irrelevant data  
- Churn distribution analysis  
- Monthly charges vs churn  
- Tenure vs churn  
- Contract type impact  
- Correlation heatmap  
- Final insights and recommendations  

Tools used: **Pandas, NumPy, Matplotlib, Seaborn**

---

## 📂 Folder Structure

Customer-Churn-Analysis/  
│── data/  
│   └── Telco_Customer_Churn.csv  
│── notebooks/  
│   └── churn_analysis.ipynb  
│── images/  
│   ├── churn_count.png  
│   ├── monthly_charges_dist.png  
│   ├── monthly_charges_vs_churn.png  
│   ├── tenure_vs_churn.png  
│   └── correlation_heatmap.png  
│── README.md  

---

## 📊 Key Insights

- Month-to-month contract customers churn the most.  
- Higher monthly charges strongly increase churn rate.  
- New customers (0–6 months tenure) leave more often.  
- Electronic Check users have the highest churn percentage.  
- Fiber Optic internet users churn more than DSL users.  
- Senior citizens churn more than younger customers.

---

## 💡 Recommendations

- Improve onboarding support for new customers.  
- Offer incentives for long-term contract plans.  
- Enhance service quality for Fiber Optic users.  
- Reduce friction in electronic check payments.  
- Promote add-on services like Tech Support and Online Security.

---

## 🚀 How to Run This Project

1. Download or clone this repository.  
2. Open the **notebooks** folder.  
3. Run the notebook: `churn_analysis.ipynb`  
4. Ensure the dataset is inside the **data** folder.  
5. Run all cells to reproduce the full analysis and charts.

---

## 🙋‍♂️ Author

**Ayush Saini**  
Aspiring Data Analyst
