# Mini-Project-Excel-Power-BI
This project involves cleaning, transforming, and analysing raw data using Excel and creating an interactive Power BI dashboard to derive meaningful business insights. 
# Production Productivity Analysis Dashboard

## Garments Production Analysis Dashboard

## 🚀 Project Overview

This project focuses on analyzing manufacturing production data to identify key performance trends, productivity gaps, workforce efficiency, incentive impact, overtime utilization, and operational improvement opportunities.

The project uses **Microsoft Excel** for data preparation and **Power BI** for advanced analytics, data modelling, DAX calculations, and interactive dashboard development.

🎯 **Objective:**  
Transform raw production data into meaningful business insights that support data-driven decisions and improve overall manufacturing efficiency.

---

# 🛠️ Tools & Technologies

## 📗 Microsoft Excel

🔹 Data cleaning and preprocessing  
🔹 Data transformation and standardization  
🔹 Handling missing and inconsistent values  
🔹 Pivot Table creation for analysis  
🔹 Initial exploration of production trends  

### Example:

**Before Data Cleaning**

| Department | Productivity | Incentive |
|------------|-------------|-----------|
| sewing | 0.80 | 1800 |
| Sewing | 0.82 | 2000 |
| FINISHING | 0.85 | 3000 |

⬇️ **After Standardization**

| Department | Productivity | Incentive |
|------------|-------------|-----------|
| Sewing | 0.80 | 1800 |
| Sewing | 0.82 | 2000 |
| Finishing | 0.85 | 3000 |

---

## 📊 Power BI

🔹 Data modelling and relationship creation  
🔹 DAX measure development  
🔹 KPI calculation  
🔹 Interactive dashboard design  
🔹 Business performance visualization  

---

# 🔄 Project Workflow

## 1️⃣ Data Preparation (Excel)

Raw manufacturing data was cleaned and transformed to make it analysis-ready.

✨ Activities Performed:

✔ Removed duplicate records  
✔ Standardized department and team names  
✔ Corrected data formats  
✔ Prepared calculated fields  
✔ Created summarized analysis tables  

---

# 2️⃣ Data Analysis Using Pivot Tables

Excel Pivot Tables were used to analyze department, team, productivity, and production performance.

### 📌 Example: Department Productivity Analysis

| Department | Actual Productivity | Target Productivity |
|------------|--------------------|--------------------|
| Sewing | 0.722 | 0.724 |
| Finishing | 0.753 | 0.737 |

💡 **Insight:**  
Finishing department achieved higher productivity and exceeded its target compared to Sewing.

---

# 3️⃣ Power BI Data Modelling

A structured data model was created to connect multiple datasets and improve reporting accuracy.

### Data Model Structure:

🔗
Garments Prouctivity DB
🔗
Measures table


✨ Modelling Activities:

✔ Created table relationships  
✔ Developed calculated measures  
✔ Built KPI metrics  
✔ Improved dashboard performance  

---

# 4️⃣ DAX Calculations

DAX measures were created to calculate important business metrics.

### 📈 Productivity Achievement %

```DAX
Productivity Achievement % =
DIVIDE(
    SUM(Data[Actual_Productivity]),
    SUM(Data[Target_Productivity])
)

📌 Purpose:
Measures actual productivity performance against planned targets.

📦 Total Production
Total Production =
SUM(Data[Production])

📌 Purpose:
Tracks overall production output.

5️⃣ Interactive Power BI Dashboard

The dashboard provides a complete view of manufacturing performance.

📌 Key Performance Indicators (KPIs)

📍 Total Production
📍 Actual Productivity
📍 Target Productivity
📍 Total Incentive
📍 Overtime Hours
📍 Idle Time
📍 Workforce Strength

📊 Dashboard Insights
🏭 Department Performance
Department	Productivity
Finishing	0.753
Sewing	0.722

💡 Insight:
Finishing demonstrated better productivity efficiency with lower workforce dependency.

👥 Team Performance Analysis
Team	Productivity
Team 1	1.1204
Team 2	1.1081
Team 4	1.0966

💡 Insight:
Teams 1, 2, and 4 were identified as top-performing teams based on productivity.

⏱️ Idle Time Analysis
Team	Idle Time
Team 7	287 Minutes
Team 8	313 Minutes

💡 Insight:
Higher idle time indicates opportunities for improving workforce utilization and workload balancing.

💰 Incentive & Productivity Analysis

💡 Insight:
Employees with higher productivity levels generally received higher incentives, supporting performance-based reward systems.

📈 Business Insights Generated

✨ Identified productivity leaders and improvement areas
✨ Compared actual performance against targets
✨ Analysed workforce utilization efficiency
✨ Evaluated overtime effectiveness
✨ Monitored idle time impact on production
✨ Studied incentive impact on employee performance
✨ Recommended strategies for operational improvement

🚀 Improvement Recommendations

🔹 Optimize workforce allocation between departments
🔹 Reduce idle time through better scheduling
🔹 Improve Sewing productivity through skill development
🔹 Balance production flow between Sewing and Finishing
🔹 Reduce unnecessary overtime dependency
🔹 Improve planning for frequent style changes
🔹 Strengthen performance-based incentive programs

📂 Project Structure
📁 Production-Analytics
│
├── 📄 Raw_Data.xlsx
├── 📄 Cleaned_Data.xlsx
├── 📊 Production_Dashboard.pbix
├── 📄 README.md
│
└── 📁 Screenshots
        └── Dashboard_View.png
🎯 Project Outcome

This project demonstrates how raw manufacturing data can be converted into actionable insights using Excel and Power BI.

The final dashboard enables decision-makers to:

📌 Monitor productivity performance
📌 Identify operational bottlenecks
📌 Improve workforce utilization
📌 Reduce production losses
📌 Make data-driven improvement decisions

⭐ Skills Demonstrated

📘 Data Cleaning
📘 Data Transformation
📘 Excel Pivot Analysis
📘 Power BI Dashboard Development
📘 Data Modelling
📘 DAX Calculations
📘 Business Intelligence Reporting
📘 Manufacturing Analytics

⭐ Built with Excel + Power BI | Turning Data into Business Decisions
