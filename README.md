# Hospital Emergency Room Analysis Dashboard

An **Excel-based healthcare analytics project** that analyzes emergency room patient activity across admissions, waiting time, satisfaction, attendance status, demographics, department referrals, and daily trends.

The project transforms a raw patient-level dataset into **Pivot Table analysis, KPI views, and an interactive Excel dashboard**.

## At a Glance

| Metric | Value |
|---|---:|
| Patient records | 9,216 |
| Source columns | 12 |
| Data period | Apr 1, 2023 – Oct 30, 2024 |
| Unique admission dates | 579 |

> **Important:** The dashboard screenshot currently shows a **January-filtered view**. Metrics from that view should not be treated as totals for all 9,216 records.

## Business Questions

- How many patients visited the emergency department?
- What proportion of patients were admitted?
- How many patients experienced delays?
- What is the average waiting time?
- What is the average patient satisfaction score?
- Which age groups and genders are most represented?
- Which departments receive the most referrals?
- How does patient volume change by day?
- How do waiting time and satisfaction change over time?

## Analysis Workflow

```text
Raw CSV
   ↓
Data organization
   ↓
Pivot Tables & KPI calculations
   ↓
Admission / attendance analysis
   ↓
Demographic & referral analysis
   ↓
Daily trend analysis
   ↓
Interactive Excel Dashboard
```

## Dashboard

The dashboard brings the analysis together across:

- Patient volume
- Admission status
- Waiting time
- Patient satisfaction
- Attendance status
- Age groups
- Gender
- Department referrals
- Daily trends

The repository includes a dashboard preview in `Final Dashboard of Hospital Emergency Analysis.png` and the Excel workbook used for the analysis.

## Current Filtered View

The documented January-filtered dashboard view contains:

| KPI | January view |
|---|---:|
| Patients | 513 |
| Average wait time | 36.32 min |
| Average satisfaction | 4.96 |
| Admitted | 269 (52.44%) |
| Not admitted | 244 (47.56%) |
| Delayed | 316 |
| On time | 197 |

### Demographics

- Male: **272**
- Female: **241**
- The **0–09** age group has the highest patient count in this filtered view.

### Department Referrals

- General Practice: **103**
- Orthopedics: **65**
- Cardiology: **14**
- Physiotherapy: **14**
- Neurology: **9**
- Renal: **5**
- Gastroenterology: **4**
- No recorded department referral: **299**

These values describe the **current filtered dashboard view**, not the full dataset.

## Skills Demonstrated

- Microsoft Excel
- Pivot Tables
- KPI development
- Data aggregation
- Percentage calculations
- Date-based analysis
- Trend analysis
- Demographic segmentation
- Dashboard design
- Data visualization
- Business intelligence

## Tools

- **Microsoft Excel** — analysis, Pivot Tables, KPI calculations, filtering, and dashboard development
- **CSV** — raw data source
- **Git & GitHub** — version control and project publishing

## Project Files

```text
hospital-emergency-dashboard/
│
├── Final Dashboard of Hospital Emergency Analysis.png
├── Hospital Emergency Pivot Report.xlsx
├── Hospital Emergency Room Data.csv
├── Hospital_Logo.png
├── .gitignore
└── README.md
```

| File | Purpose |
|---|---|
| `Final Dashboard of Hospital Emergency Analysis.png` | Dashboard preview |
| `Hospital Emergency Pivot Report.xlsx` | Pivot analysis and dashboard workbook |
| `Hospital Emergency Room Data.csv` | Raw patient dataset |
| `Hospital_Logo.png` | Dashboard visual asset |

## Limitations

- The displayed dashboard metrics are from a filtered January view.
- The project is based on historical dataset records rather than live hospital data.
- The analysis is descriptive; no forecasting or predictive modeling is included.
- Full dashboard interactivity requires Excel-compatible software.

## Potential Improvements

- Add year-over-year comparisons.
- Add automated refresh from a database.
- Extend the analysis to peak-period detection and forecasting.
- Rebuild the dashboard in Power BI for broader distribution.

## Portfolio Relevance

This project demonstrates how Excel can be used to move from **raw operational data → structured analysis → KPI reporting → dashboard communication** in a healthcare context.

## Author

**Bhaskar Nakka**  
Data Analyst | SQL · Python · Excel · Tableau · Power BI