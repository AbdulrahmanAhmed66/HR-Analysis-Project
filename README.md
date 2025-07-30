# 📊 HR Project – Excel Dashboard

### 🔗 [My LinkedIn](https://www.linkedin.com/in/abdulrahman-ahmed66)
### 📥 [Download the Excel File](HR%20project.xlsx?raw=true)

<br>
<div align="center">
  <img src="HR Project Using Excel/Screenshot (18).png?raw=true" alt="Dashboard Banner" width="1000" height="500">
</div>

---
## 📝 Introduction
<details>
  <summary><strong>📌 Overview (click)</strong></summary>

### **Overview**  
> This Excel project focuses on analyzing Human Resources (HR) data to uncover patterns and trends that support effective workforce management.  
> Using Excel's powerful tools such as Power Query, formulas, and PivotTables, I transformed raw departmental data into a unified, clean, and interactive dashboard.  
> The analysis provides deep insights into employee demographics, performance, and experience across departments.

</details>

<details>
  <summary><strong>📂 Data Sources (click)</strong></summary>

### **Data Sources**  
> The project uses employee data from **five key departments**:

1. **Departmental Tables**  
   - Source: Sales, Marketing, IT, HR, and Finance  
   - Fields: `Employee ID`, `Name`, `Department`, `Date of Birth`, `Hire Date`, `Performance Score`

2. **Appended Master Table**  
   - Combined all departmental datasets into one unified table  
   - Additional Calculated Fields:
     - `Age` (based on Date of Birth)  
     - `Years of Experience` (based on Hire Date)  
     - `Performance Category`  
     - `Average Performance Score`

> Data cleaning and transformations were handled through Power Query and Excel formulas, ensuring consistency across departments.

</details>

---

## 🎯 Case Study  
This project represents a real-world HR scenario where employee data was stored separately across various departments, making analysis inefficient and time-consuming.

To address this, I used **Power Query** to:
- Append departmental data into a master dataset  
- Clean and standardize data fields  
- Add calculated columns for age, experience, and performance metrics  

The main objective was to build a professional **HR dashboard** that enables:
- Monitoring performance by department  
- Analyzing relationships between experience and performance  
- Exploring employee demographics and role distribution  
- Supporting HR decisions regarding training, retention, and promotions

> ✅ This project demonstrates how Excel can be effectively used in HR analytics to drive smart, people-focused decisions — without the need for external BI tools.

---

## 📊 Main KPIs

- **👥 Total Employees** – 94  
- **💰 Total Salary** – 1,248,578  
- **💵 Average Salary** – 13,283  
- **🎂 Average Age** – 51 years  
- **📈 Average Experience** – 14 years  

---
## ⚙️ Process

1. **Data Aggregation**  
   - Combined employee data from five departments: Sales, Marketing, IT, HR, and Finance  
   - Used **Append Queries** in Power Query to merge all departmental datasets into a unified table

2. **Data Cleaning**  
   - Removed duplicate records, handled missing values, standardized job titles and departments  
   - Ensured consistency in formats (e.g., dates, salary, performance scores)

3. **Feature Engineering**  
   - Created new calculated columns:  
     - `Age` – based on Date of Birth  
     - `Years of Experience` – based on Hire Date  
     - `Performance Category` – grouped based on performance score  
     - `Average Performance` – for use in aggregated charts

4. **Data Modeling**  
   - Structured the final dataset to support dynamic analysis via PivotTables  
   - Enabled filtering by `Department`, `Education`, and `Location` through slicers

5. **Dashboard Design**  
   - Designed a clean and interactive HR dashboard with:  
     - KPIs (Total Employees, Average Age, Avg. Salary, etc.)  
     - Charts for experience, salary, and performance by various dimensions  
     - Slicers for quick filtering by department, education, and location

---

## 🔍 Key Insights

1. **Sales Manager** and **HR Contributor** roles have the highest average years of experience across all departments.
2. **Master’s degree holders** show the highest average performance, followed by Bachelor's and then Diploma holders.
3. **Finance and IT departments** offer the highest average salaries among all departments.
4. A **positive correlation** is observed between **years of experience and employee performance**.
5. Most employees are concentrated in the **Sales** department, particularly in Product and Sales-related roles.
6. **Experience distribution** shows that the majority of employees have between **6 to 14 years** of experience.
7. **Average employee age** is relatively high (around 51), which may impact future HR planning and succession strategies.

---

## 💡 Conclusion

This Excel-based HR analytics project highlights how powerful insights can be extracted from employee data using Excel’s built-in capabilities—**Power Query**, **PivotTables**, and effective **Dashboard Design**.

By aggregating and analyzing data across departments, education levels, and job roles, the final dashboard enables HR professionals to:
- Understand workforce structure  
- Evaluate performance trends  
- Analyze experience and salary distributions  
- Support strategic decision-making in recruitment, training, and employee development

✅ The project demonstrates that even without external BI tools, Excel can serve as a practical and efficient platform for HR data analysis and visualization.
