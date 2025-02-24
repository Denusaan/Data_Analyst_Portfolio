# 📉 Customer Churn Analysis  

## 📌 Overview  
The **Customer Churn Analysis** project aims to understand customer attrition patterns and provide actionable insights to improve retention. Using **Power BI**, the project explores customer demographics, behavior, and churn rates to optimize marketing and engagement strategies.  

---

## 🛠 Tools Used  
- **Power BI** – Data visualization & dashboard creation  
- **DAX (Data Analysis Expressions)** – Calculations & metrics  
- **Excel/CSV Files** – Data source for demographics, behavior, and churn status  

---

## 🔍 Approach and Process  

### 1️⃣ Data Cleaning  
- Changed first row as headers & modified column values  
- Handled missing values & removed duplicates  
- Converted data types for accurate calculations  

### 2️⃣ Data Modeling  
- **Fact Table:** Main customer data  
- **Dimension Tables:**  
  - `Age Range` – Categorized age groups  
  - `Balance Range` – Grouped balance categories  
  - `Credit Score Range` – Classified credit segments  
- **Created using Power BI's Reference Table feature**  

### 3️⃣ DAX Measures  
- **Total Customers:** `COUNT(customer_id)`  
- **Churn Customers:** `COUNT(customer_id)` where `Churn Status = "Churned"`  
- **Churn Rate:** `[Churn Customers] / [Total Customers]`  

### 4️⃣ Power BI Visualizations  
- **Slicers** – Filter data by churn status  
- **Gauge Chart** – Displays churn rate  
- **Donut Charts** – Breakdown of customers by gender, credit card ownership, products, and country  
- **Comparative Charts** – Analyzing total customers vs. churn rate by age, balance, and credit score range  

---

## 📊 Key Insights  
✅ High churn rates in the **46-60 age group**, possibly due to retirement  
✅ Customers with **credit scores below 400** are more likely to churn  
✅ **Lower balance customers** tend to leave earlier  

## 💡 Recommendations  
🚀 **Targeted Retention Campaigns** – Personalized offers for high-risk customers  
🚀 **Product Enhancements** – Improve services with low engagement  
🚀 **Proactive Outreach** – Customer support for at-risk segments  

---

## 📢 Conclusion  
This **Customer Churn Analysis** project leverages Power BI’s capabilities in data modeling, visualization, and DAX calculations to **identify at-risk customer segments and optimize retention strategies**.  

