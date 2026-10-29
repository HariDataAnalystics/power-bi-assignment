# Power BI Assignment 2 – DAX Calculations & Data Visualization

## 📌 Project Overview

This project focuses on analyzing an **E-Commerce Sales Dataset** using Microsoft Power BI. The objective is to apply DAX (Data Analysis Expressions) to create calculated columns and measures, develop interactive visualizations, and generate meaningful business insights related to sales performance, profitability, customer orders, and sales targets.

This project is part of my Data Analytics learning journey as an **Aspiring Data Analyst**, where I am developing practical skills in data analysis, business intelligence, and data visualization.

## 🎯 Project Objectives

- Create calculated columns and measures using DAX.
- Analyze sales, revenue, profit, and order performance.
- Compare actual sales against sales targets.
- Identify monthly sales trends and regional sales patterns.
- Build interactive visualizations for business reporting.
- Present data-driven insights through Power BI dashboards.

## 📂 Dataset Description

The project uses three datasets:

| Dataset | Key Attributes |
|---|---|
| List of Orders | Order ID, Order Date, Customer Name, City, State, Category, Amount, Profit |
| Order Details | Order ID, Category, Sub-Category, Quantity, Amount, Profit |
| Sales Target | Category, Month of Order Date, Target |

The existing data model and relationships were created during the previous assignment.

## 🧮 DAX Calculations

### 1. Calculated Columns

The following calculated columns are created in the **Order Details** table:

- **Category Type:** Combines Category and Sub-Category into a single column.
- **Revenue per Order:** Calculates revenue using Amount × Quantity.
- **Sales Category:** Categorizes sales as Above Average or Below Average based on the Amount value.

### 2. Calculated Measures

The following DAX measures are developed:

- **Order Count:** Calculates the total number of orders in the Order Details table.
- **Average Profit in Delhi:** Calculates the average profit for orders placed in Delhi.
- **Year-to-Date (YTD) Sales:** Calculates cumulative sales from the beginning of the year up to the current order date.

## 📊 Power BI Visualizations

The following visualizations are created to analyze e-commerce business performance:

| No. | Visualization | Purpose |
|---|---|---|
| 1 | Clustered Column Chart | Compare actual sales and sales targets by category |
| 2 | Donut Chart | Analyze maximum profit margin by sub-category |
| 3 | Line Chart | Identify monthly sales trends |
| 4 | Scatter Chart | Compare profit and quantity by sub-category |
| 5 | Card Visuals | Display total sales amount and sales target |
| 6 | Multi-row Card | Display the minimum target for each segment |
| 7 | Matrix | Compare actual sales and targets across categories and months |
| 8 | Map | Analyze geographic sales distribution by city |
| 9 | Treemap | Visualize sales distribution by sub-category |
| 10 | Funnel Chart | Analyze order counts across different states |

## 🛠️ Tools & Technologies

- **Microsoft Power BI Desktop** – Data modeling and visualization
- **DAX** – Calculated columns, measures, and business metrics
- **E-Commerce Sales Dataset** – Sales performance analysis
- **GitHub** – Project documentation and portfolio management

## 💡 Key Learning Outcomes

Through this assignment, I practiced:

- Writing DAX expressions for calculated columns and measures.
- Applying aggregation and time-intelligence calculations.
- Comparing sales performance against business targets.
- Selecting appropriate visualizations for different analytical questions.
- Building structured reports to support data-driven decision-making.
- Improving analytical thinking and business intelligence skills.

## 📁 Project Files

- `README.md` – Project overview, objectives, tools, and documentation.
- `Power BI Report (.pbix)` – Interactive Power BI report, if included.
- `Dashboard Screenshots/` – Screenshots of completed visualizations, if included.
- `Dataset/` – Source datasets, if permitted to share.

## 🚀 Conclusion

This project demonstrates my practical learning in DAX calculations and Power BI data visualization using an e-commerce sales dataset. It helped me understand how to transform sales data into meaningful metrics and visual reports for business analysis.

I am continuously improving my skills in **Data Analytics, Excel, SQL, Python, and Power BI** to prepare for opportunities as a Data Analyst.

## 👨‍💻 About Me

**Hariharan A.**  
Aspiring Data Analyst | Final-Year Biomedical Engineering Student

I am passionate about data analysis, problem-solving, and transforming raw data into meaningful business insights. I am building my portfolio through practical projects and continuous learning.

**GitHub:** [Add your GitHub Profile Link]  
**LinkedIn:** [Add your LinkedIn Profile Link]

---

⭐ Thank you for visiting my project repository!

