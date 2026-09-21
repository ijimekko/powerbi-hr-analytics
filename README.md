# HR Employee Engagement Dashboard (Power BI)

An interactive Power BI dashboard for analyzing employee engagement, satisfaction, and turnover.

## 📊 About

This dashboard combines employee survey data, HR records, and training costs so HR teams can track key workforce metrics over time and across departments.

## 📄 Report Pages

| Page | Description |
|---|---|
| **Engagement** | Employee engagement levels by department |
| **Satisfaction** | Employee satisfaction levels by department |
| **WL Balance** | Work-life balance trend over time |
| **Engagement (%)** | Average engagement % by department |
| **Satisfaction (%)** | Average satisfaction % by department |
| **WL Balance (%)** | Average work-life balance % by month |
| **Terminations** | Employee termination trend over time |
| **Dashboard** | Summary page: KPIs, gauges, training costs, training program breakdown, and performance score distribution |

## 🗂 Data Sources

- `employee_data` — department, status, exit date, performance score
- `employee_engagement_survey_data` — survey results (Engagement, Satisfaction, Work-Life Balance)
- `training_and_development_data` — training programs and their cost
- Supporting calendar tables for time-based analysis

## 🛠 Tech Stack

- Power BI Desktop (.pbix)
- DAX measures for percentage-based KPIs

## 🚀 Getting Started

1. Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
2. Open `PowerBI_HR_Analysis.pbix`
