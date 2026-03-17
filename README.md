# HR Analytics Dashboard 📊

An interactive HR Analytics Dashboard built entirely in Microsoft Excel,
designed to monitor and analyze HR department data across 50 employees.

## 📸 Preview
<img width="1443" height="824" alt="Screenshot 2026-03-18 004649" src="https://github.com/user-attachments/assets/91ed94a2-4533-4285-812f-408eb3447fc2" />

## 🛠️ Built With
- Microsoft Excel
- PivotTables & PivotCharts
- Slicers
- Data Modeling & Formulas

## 📊 Dashboard Features
- **Employee Overview** — Total headcount with gender split (Male/Female %)
- **Skills Breakdown** — Count of employees per skill
- **Work Location** — Branch Office, Head Office, Remote distribution
- **Age Range** — Employees by age group and gender
- **Leave Tracking** — Total day off by job title
- **Avg Performance Rating** — Overall average rating across all employees
- **Avg Salary by Job Title** 
- **Employees per Region** — Headcount by geographic region
- **Employment Status** — Full-Time, Part-Time, Contract breakdown

## 🔍 Filters / Slicers
- Filter by **Gender** (Male / Female)
- Filter by **Department** (Finance, HR, IT, Marketing, Operations)
- All visuals update dynamically when filters are applied

## 📁 Dataset
- 50 employees
- 21 columns including: Employee ID, Gender, Age, Department,
  Job Title, Salary, Performance Rating, Skills, Work Location, and more

## 📐 Data Modeling
- Excel Table named `Table1` as the single source of truth
- PivotTables connected to all charts and KPI cards
- All slicers connected via Report Connections to every PivotTable
- Formulas used:
  - `COUNTIF` — for skill and gender counts
  - `AVERAGEIF` — for salary and performance by category
  - `% of Grand Total` — for gender and status percentages

## 🚀 How to Use
1. Download the `.xlsx` file
2. Open in Microsoft Excel 
3. Enable editing if prompted
4. Use the **Gender** and **Department** slicers to filter the dashboard
5. All charts and KPIs will update automatically

## 📌 Notes
- Best viewed on Excel 2016 or later
- Do not delete any PivotTable sheets — they power the dashboard


