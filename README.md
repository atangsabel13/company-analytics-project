# 📊 Workforce & Compensation Dashboard — Power BI

A three-page Power BI dashboard analyzing employee headcount, compensation, and performance across a 1,000+ employee dataset spanning five industries — built with a relational data model and custom DAX measures.

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-F2C811?logo=powerbi&logoColor=black)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

---

## 📌 Overview

This dashboard gives HR and business leaders a single place to explore workforce composition, pay, and performance — from a company-wide executive summary down to department- and region-level detail.

**Objectives:**
1. Model relationships across employee, compensation, and company data
2. Build reusable DAX measures for headcount, pay, age, and performance metrics
3. Design three purpose-built report pages for different audiences — executives, HR/people analysts, and department managers

---

## 🗂️ Data Model

Three related tables:

| Table | Key fields |
|---|---|
| `Staff` | Employee ID, Department, Job Title, Salary Band, Hire Date |
| `Employment` | Salary (USD), Bonus (USD), Performance, Work Year, Experience Level |
| `Companies` | Company Name, Industry, Region |

**Custom DAX measures:**
- `Number of Employees`
- `Total Number of Companies`
- `Average Age`
- `Average Salary`
- `Average Performance Score`
- `% High Performers`

---

## 📄 Report Pages

### 1. Executive Overview
Company-wide headline numbers — total employees, total companies, and headline compensation KPIs — alongside:
- **Number of Employees Per Department** (clustered bar)
- **Number of Companies Per Industry** (funnel)
- **Average Salary Per Year** (line)
- A key-influencers visual surfacing what drives the headline metrics

### 2. Employee Analysis
A people-focused view of the workforce, with KPI cards for % High Performers, Average Age, and Total Employees, plus:
- **Number of Employees Per Industry** (pie)
- **Number of Employees Per Level** (donut)
- **Average Salary Per Year** (line)
- **Number of Employees Hired Per Year** (line)

### 3. Management Dashboard
A performance-and-pay view for department and regional managers, with KPI cards for headcount, salary, and bonus totals, plus:
- **Average Performance by Department** (clustered bar)
- **Employee Performance by Region** (clustered bar)
- **Number of Employees Per Region** (line)

---

## 🛠️ Tools & Skills Demonstrated

- Power BI data modeling across multiple related tables
- DAX measures (aggregations, ratios, and custom calculations)
- A mix of visual types: cards, clustered bar, line, pie, donut, funnel, and key-influencers charts
- Multi-page report design tailored to different audiences (executive, HR, management)

---

## 📁 Files in This Repository

| File | Description |
|---|---|
| `POWER_BI_PRO_1.pbix` | The full interactive Power BI report — open in Power BI Desktop to filter, drill down, and explore |
| `POWER_BI_PRO_1.pdf` | A static export of all three pages, for quick viewing without Power BI Desktop installed |

---

## 🚀 How to Use

1. Open `POWER_BI_PRO_1.pbix` in Power BI Desktop to interact with the report — cross-filter visuals by clicking any chart, or use the key-influencers visual to explore drivers.
2. Don't have Power BI Desktop? Open `POWER_BI_PRO_1.pdf` for a static view of all three pages.

---

## 📬 Contact

**Abel Atangs**
📧 abelatangs7@gmail.com
🔗 [LinkedIn](https://linkedin.com/in/abel-atangs03) · [GitHub](https://github.com/atangsabel13)
