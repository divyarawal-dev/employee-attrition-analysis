# Employee Attrition Analysis

Multi-domain SQL analysis of 1,470 employee records (IBM HR Analytics dataset) 
examining attrition drivers, satisfaction, compensation, and career/tenure patterns.
Group project — 4 contributors, each owning one analytical domain.

**My section: Career & Tenure** — composite risk-scoring model using chained CTEs 
to flag at-risk employees before departure (see /queries/career_tenure.sql).

## Full Report
[View Full Report (PDF)](docs/Final_Project_Report.pdf)

## Key Findings
- Company-wide attrition rate: 16.1%
- Highest risk window: new hires in year one (34.88% attrition)
- Composite risk model flagged 253 employees (17.1%+3.4%) as High/Critical Risk

## Tools
MySQL Workbench 8.0, Microsoft Excel
