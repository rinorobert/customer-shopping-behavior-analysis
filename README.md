# Customer Shopping Behavior Analysis

This project analyzes customer shopping patterns to uncover insights into purchasing behavior, spending trends, and factors influencing buying decisions. The objective is to transform raw transactional data into meaningful insights that support data-driven business decisions using an end-to-end analytics workflow.

This project is **completed** and includes:
- 📄 A detailed project report (PDF)
- 📊 A summarized presentation (PPT)

---

## 🎯 Project Scope & Objectives

- Understand how different customer segments contribute to revenue  
- Analyze the impact of discounts, subscriptions, and shipping types  
- Identify high-performing products and categories  
- Segment customers based on purchase history and behavior  
- Uncover trends through exploratory data analysis (EDA)  
- Communicate insights through dashboards and documentation  

---

## ✅ Project Status: Completed

### 🔹 Data Preparation & Feature Engineering

- Dataset used: `customer_shopping_behavior.csv`  
- Data cleaned and preprocessed using Python (pandas)  
- Missing values in **Review Rating** handled using category-wise median  
- Column names standardized using **snake_case**  
- Feature engineering performed:
  - `age_group` created using quantile-based binning
  - `purchase_frequency_days` created by mapping purchase frequency to numeric values  
- Data quality verified using sample outputs  

---

### 🔹 Exploratory Data Analysis (Python)

- Distribution analysis of age, purchase amount, and purchase frequency  
- Behavioral comparison across age groups and subscription status  
- Initial visual exploration using Pandas and Matplotlib  
- Insights documented alongside the analysis code  

---

### 🔹 Database Integration

- Python connected to PostgreSQL using SQLAlchemy  
- Cleaned dataset loaded into relational tables  
- SQL-based analysis performed on the database  

---

### 🔹 SQL Analysis (PostgreSQL)

- Revenue comparison by gender  
- Spending behavior of subscribed vs non-subscribed customers  
- Impact of discounts on purchasing behavior  
- Comparison of average purchase amounts across shipping types  
- Customer segmentation into New, Returning, and Loyal  
- Repeat buyers and subscription likelihood analysis  
- Product- and category-level performance analysis  
- Revenue contribution by different age groups  

All SQL queries and explanations are documented in the project report.

---

### 🔹 Data Visualization (Power BI)

- Power BI dashboard created using the cleaned dataset  
- Interactive visuals for:
  - Revenue trends  
  - Customer segments  
  - Product performance  
- Filters for age group, gender, subscription status, and category  
- Dashboard designed to support business-level decision making  

---

## 📄 Project Documentation

- **Customer Shopping Behavior Analysis.pdf** – Detailed project report  
- **Customer-Shopping-Behavior-Analysis.pptx** – Summary presentation  

---

## 🛠️ Tools & Technologies Used

- Python (Pandas, Matplotlib, SQLAlchemy)  
- PostgreSQL & SQL  
- Jupyter Notebook  
- Power BI  
- VS Code  
- Git & GitHub  

---

## 📌 Key Learnings

- End-to-end data analytics workflow  
- Practical data cleaning and feature engineering  
- SQL-based business analysis on real datasets  
- Converting data insights into business recommendations  
- Presenting results through reports and dashboards  

---

## 👨‍🎓 About Me

I’m **Rino Robert**, a B.Tech student in **Artificial Intelligence & Data Science**, focused on building practical, end-to-end analytics projects aligned with real-world industry workflows.

📧 Email: rinorobert710@gmail.com  
🔗 LinkedIn: https://www.linkedin.com/in/rino-robert/