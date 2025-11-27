🧑‍💼 Customer Churn Analysis

This project explores telecom customer data to understand why customers leave (churn).
I analyzed contract types, service usage, payment methods, and customer behavior to identify patterns that lead to churn.
The goal is to help the business understand what drives customer loss and how they can reduce it.

📌 What This Project Covers
Loaded and cleaned the churn dataset
Converted important columns to correct data types
Explored churn distribution
Analyzed monthly charges, tenure, and contract types
Boxplots for key features
Correlation heatmap
Business insights and recommendations
Tools used: Pandas, NumPy, Matplotlib, Seaborn

📂 Folder Structure

Customer-Churn-Analysis/
│── data/
│ └── Telco_Customer_Churn.csv
│── notebooks/
│ └── churn_analysis.ipynb
│── images/
│ ├── churn_count.png
│ ├── monthly_charges_dist.png
│ ├── monthly_charges_vs_churn.png
│ ├── tenure_vs_churn.png
│ └── correlation_heatmap.png
│── README.md

📊 Key Insights

Month-to-month contract customers churn the most.
Higher monthly charges lead to higher churn.
New customers (0–6 months tenure) leave more often.
Electronic check users show the highest churn rate.
Fiber Optic internet users churn more than DSL customers.
Senior citizens have a higher churn percentage.

💡 Recommendations

Provide better onboarding for new customers.
Encourage customers to move to long-term contracts.
Improve experience for Fiber Optic users.
Offer better alternatives to electronic check payments.
Promote services like Tech Support and Online Security.

🚀 How to Run This Project

Download or clone this repository.
Open the notebooks folder.
Run the notebook: churn_analysis.ipynb
Make sure the churn CSV file is inside the data folder.
Run all cells to reproduce the analysis and charts.
