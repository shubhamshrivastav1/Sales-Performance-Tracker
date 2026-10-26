# 📊 Sales Performance Tracker – Excel Dashboard

An interactive **Sales Performance Dashboard built in Microsoft Excel** to analyze employee-wise sales, monitor target achievement, and compare sales performance across multiple cities.

This project transforms raw sales data into an organized visual dashboard, helping users identify sales trends, evaluate employee performance, and track progress toward business targets.

## 📌 Project Overview

The Sales Performance Tracker contains sales records for 100 employees across eight cities. It includes an interactive dashboard with performance tables, target achievement analysis, and charts for effective sales reporting.

The workbook demonstrates practical Excel skills in data analysis, reporting, dashboard design, and business intelligence.

## 🔗 Live Excel Dashboard

**View or download the Excel workbook:**

📊 [**Open Sales Performance Tracker Dashboard**](https://drive.google.com/file/d/1mVd71xd55w1IvkcVO6CF9O5UM1-4Gnly/view?usp=drive_link)

Explore the Excel workbook to review employee-wise sales, city-wise performance, target achievement, and dashboard visualizations.

> **Note:** Ensure that Google Drive sharing permissions allow viewers to access the file. This link opens the Excel file hosted on Google Drive; it is not a live website dashboard.
>
> ## ScreenShorts
> Row Data
> <img width="1607" height="953" alt="Screenshot 2026-10-26 165851" src="https://github.com/user-attachments/assets/943b13c4-4542-4da7-9fbf-708864257cef" />

## Chart using Data

<img width="1811" height="1008" alt="Screenshot 2026-10-26 165831" src="https://github.com/user-attachments/assets/4398d269-730b-409c-a286-491adaf551db" />



## ✨ Key Features

- **Interactive City Filters:** Explore sales performance across Chennai, Delhi, Mumbai, Nagpur, Patna, Pune, Ranchi, and Surat.
- **Employee-Wise Sales Analysis:** Compare total sales achieved by individual sales executives.
- **Target Achievement Analysis:** Track the percentage of assigned sales targets achieved.
- **Target Gap Monitoring:** Identify how far employees are below their assigned sales targets.
- **Multiple Dashboard Views:** Explore sales summaries, employee comparisons, target achievement, and performance gaps.
- **Visual Data Representation:** Analyze performance using bar charts, pie charts, and line charts.
- **Daily Sales Tracking:** Analyze sales recorded over five days.
- **Conditional Formatting:** Highlight performance levels and target gaps for easier interpretation.
- **Structured Data Table:** Maintain organized employee records for reporting and analysis.

## 📈 Dashboard Highlights

### 1. Total Sales Analysis

Displays employee-wise total sales and compares sales performance using a horizontal bar chart.

### 2. Employee Performance Comparison

Provides a focused view of sales executives and their respective sales figures.

### 3. Target Achievement Analysis

Shows the percentage of assigned sales targets achieved by employees, supported by visual charts.

### 4. Away From Target Analysis

Highlights the percentage of the assigned target that remains unachieved, helping identify areas that need improvement.

## 🗂️ Dataset Information

The workbook contains the following fields:

| Column | Description |
|---|---|
| Emp Code | Unique employee identification code |
| Sales Executive | Name of the sales employee |
| Region | City assigned to the employee |
| Day1–Day5 | Daily sales figures |
| Total Sales | Total sales across five days |
| Target | Assigned sales target |
| Target Hit % | Percentage of the target achieved |
| Away From Target % | Percentage of the target remaining unachieved |

## 🧮 Key Calculations

### Total Sales

Sum of sales recorded over five days.

`Total Sales = Day1 + Day2 + Day3 + Day4 + Day5`

### Target Hit Percentage

`Target Hit % = (Total Sales / Target) × 100`

### Away From Target Percentage

`Away From Target % = ((Target - Total Sales) / Target) × 100`

*Note: These formulas assume the target is positive. When sales exceed the target, the target gap should be handled appropriately to avoid interpreting overachievement as a negative performance result.*

## 🛠️ Tools & Technologies

- Microsoft Excel
- Excel Tables
- PivotTables and PivotCharts
- Interactive filters
- Excel formulas
- Conditional formatting
- Data visualization
- Dashboard design and business reporting

## 📁 Project Structure

```text
Sales-Performance-Tracker/
│
├── Sales_Performance_Tracker_100_Employees.xlsx
├── README.md
└── screenshots/
    ├── sales-dashboard.png
    └── employee-sales-data.png
```

*The filenames above are suggested examples. Use the actual filenames of the files you upload to GitHub.*

## 🚀 How to Use

1. Clone or download this repository.
2. Open the Excel workbook in Microsoft Excel.
3. Navigate to the **DASHBOARD** sheet.
4. Select a city to explore the corresponding sales data.
5. Review employee-wise sales figures and target achievement percentages.
6. Use dashboard charts to compare employee performance.
7. Navigate to the **ROW DATA** sheet to inspect the underlying employee records.
8. Refer to the **Read Me** sheet in the workbook for any additional workbook instructions.

Alternatively, access the workbook directly through the [Google Drive link](https://drive.google.com/file/d/1mVd71xd55w1IvkcVO6CF9O5UM1-4Gnly/view?usp=drive_link).

For the best experience, use desktop Microsoft Excel, where supported interactive features are available.

## 🎯 Business Objectives

This dashboard aims to:

- Monitor employee sales performance.
- Measure progress against sales targets.
- Compare performance across cities.
- Identify employees who may need additional support.
- Improve the speed and clarity of sales reporting.
- Support data-driven business decisions.

## 💡 Skills Demonstrated

- Data organization and analysis
- Excel formula implementation
- Sales KPI calculations
- PivotTable-based analysis
- Interactive dashboard development
- Chart creation and formatting
- Conditional formatting
- Business reporting and data storytelling

## 🔮 Future Improvements

- Add monthly and quarterly sales analysis.
- Introduce top-performer rankings.
- Include average daily sales and target completion status.
- Add automated data refresh functionality.
- Integrate Power BI for advanced analytics.
- Develop an automated sales reporting system.
- Build a web-based interactive version of the dashboard.

## 👨‍💻 Author

**Shyam Shrivastav**

Aspiring Data Analyst | Microsoft Excel | Data Visualization | Business Intelligence

This project showcases practical Excel dashboard development and sales performance analysis.

## ⭐ Feedback

If you find this project useful, consider giving the repository a ⭐ on GitHub.

Suggestions and improvements are welcome!

---

**Project:** Sales Performance Tracker – Excel Dashboard  
**Primary Tool:** Microsoft Excel  
**Dataset:** 100 Employees  
**Coverage:** 8 Cities  
**Purpose:** Sales Performance Analysis and Target Monitoring
