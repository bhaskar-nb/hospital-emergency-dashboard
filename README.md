# Hospital Emergency Room Analysis Dashboard

<p align="center">
  <img src="Final Dashboard of Hospital Emergency Analysis.png" alt="Hospital Emergency Analysis Dashboard" width="100%">
</p>

An Excel-based Hospital Emergency Room Analysis Dashboard developed to analyze patient volume, admission patterns, waiting time, patient satisfaction, attendance status, demographics, and department referrals.

The project transforms raw emergency room patient data into structured Pivot Table analysis and an interactive Excel dashboard to provide a clear overview of hospital emergency department activity.

---

## Overview

Emergency departments handle patients with different demographic characteristics, admission outcomes, waiting times, satisfaction levels, and referral requirements.

This project uses a patient-level emergency room dataset containing **9,216 records** and **12 columns**. The data covers the period from **April 1, 2023 to October 30, 2024**.

The analysis was performed in Microsoft Excel using Pivot Tables, calculated metrics, filtering, grouping, and dashboard visualization.

The project focuses on questions such as:

- How many patients visited the emergency department?
- What is the distribution of patient admissions?
- How many patients experienced delays?
- What is the average patient waiting time?
- What is the average patient satisfaction score?
- Which age groups contain the most patients?
- What is the gender distribution?
- Which departments receive the most referrals?
- How does patient volume vary by day?
- How do waiting time and satisfaction change over time?

---

## Project Objectives

The main objectives of this project are to:

- Analyze emergency room patient activity.
- Understand patient admission patterns.
- Measure patient waiting time.
- Analyze patient satisfaction.
- Identify delayed and on-time patient attendance.
- Analyze patient demographics.
- Understand department referral patterns.
- Analyze daily patient trends.
- Build an interactive Excel dashboard.
- Convert raw healthcare data into meaningful analytical insights.

---

## Dataset Overview

The raw dataset contains:

| Dataset Attribute | Value |
|---|---:|
| Patient Records | 9,216 |
| Columns | 12 |
| Earliest Admission | April 1, 2023 |
| Latest Admission | October 30, 2024 |
| Unique Admission Dates | 579 |

### Dataset Columns

The CSV contains the following fields:

- Patient Id
- Patient Admission Date
- Patient First Inital
- Patient Last Name
- Patient Gender
- Patient Age
- Patient Race
- Department Referral
- Patient Admission Flag
- Patient Satisfaction Score
- Patient Waittime
- Patient Admission Flag.1

The dataset contains two admission-flag columns in the source CSV. When loaded with pandas, the duplicate column name is automatically represented as `Patient Admission Flag.1`.

---

## Excel Analysis Workflow

The project follows an end-to-end Excel analytics workflow:

1. Import the raw emergency room dataset.
2. Review the patient-level records.
3. Organize the data for analysis.
4. Create Pivot Tables.
5. Calculate key performance indicators.
6. Analyze admission status.
7. Analyze patient attendance status.
8. Create age groups.
9. Analyze gender distribution.
10. Analyze department referrals.
11. Analyze daily patient volume.
12. Calculate daily average waiting time.
13. Calculate daily average satisfaction score.
14. Apply filters for focused analysis.
15. Build the Excel dashboard.
16. Present the analysis through visualizations and KPI cards.

---

## Dashboard

The project contains a dedicated Excel **Dashboard** sheet designed to provide a visual summary of the emergency room analysis.

The dashboard includes analysis related to:

- Patient volume
- Admission status
- Waiting time
- Patient satisfaction
- Attendance status
- Age groups
- Gender
- Department referrals
- Daily trends

### Dashboard Filter

The dashboard currently has a **January month filter selected**.

Therefore, the dashboard screenshot represents a **filtered January view**, rather than all 9,216 patient records.

The underlying dataset covers April 2023 through October 2024, while the dashboard can be explored through its available filtering options in Excel.

A preview of the dashboard is included above and is stored in:

`Final Dashboard of Hospital Emergency Analysis.png`

---

## Pivot Report

The Excel workbook contains a dedicated **Pivot Report** sheet used as the analytical layer behind the dashboard.

The Pivot Report contains analysis for:

- Number of patients
- Average patient waiting time
- Average patient satisfaction score
- Daily patient trends
- Daily average waiting time
- Daily satisfaction score
- Admission status
- Admission percentage
- Age-group distribution
- Attendance status
- Gender distribution
- Department referrals
- Year-level analysis

The currently inspected Pivot Report shows **513 patients**, which corresponds to the dashboard's current filtered view and should not be interpreted as the total dataset size.

---

## Current Filtered Dashboard Analysis

With the current dashboard filter applied, the Pivot Report contains the following January-view metrics:

### Patient Overview

| KPI | Current Filtered Value |
|---|---:|
| Patients | 513 |
| Average Wait Time | 36.32 minutes |
| Average Satisfaction Score | 4.96 |

### Admission Status

| Admission Status | Patients | Percentage |
|---|---:|---:|
| Admitted | 269 | 52.44% |
| Not Admitted | 244 | 47.56% |
| Total | 513 | 100% |

### Attendance Status

| Attendance Status | Patients |
|---|---:|
| Delay | 316 |
| On Time | 197 |
| Total | 513 |

### Gender

| Gender | Patients |
|---|---:|
| Male | 272 |
| Female | 241 |
| Total | 513 |

### Age Groups

| Age Group | Patients |
|---|---:|
| 0–09 | 76 |
| 10–19 | 69 |
| 20–29 | 64 |
| 30–39 | 59 |
| 40–49 | 58 |
| 50–59 | 66 |
| 60–69 | 67 |
| 70–79 | 54 |
| Total | 513 |

### Department Referrals

| Department | Patients |
|---|---:|
| General Practice | 103 |
| Orthopedics | 65 |
| Cardiology | 14 |
| Physiotherapy | 14 |
| Neurology | 9 |
| Renal | 5 |
| Gastroenterology | 4 |

There are also **299 records without a department referral** in the current filtered view.

---

## Waiting Time Analysis

The current filtered dashboard view shows an average patient waiting time of:

**36.32 minutes**

Daily average waiting time is also included in the Pivot Report.

Analyzing waiting time can help identify changes in patient flow and periods where emergency department processing may require attention.

---

## Patient Satisfaction Analysis

The current filtered dashboard view shows an average patient satisfaction score of:

**4.96**

Daily satisfaction scores are included in the Pivot Report to provide a view of how patient experience changes across the analyzed dates.

---

## Admission Analysis

The current filtered view contains:

- **269 admitted patients**
- **244 not admitted patients**

Admitted patients represent approximately **52.44%** of the current filtered records, while approximately **47.56%** were not admitted.

This analysis provides a snapshot of admission outcomes within the selected dashboard period.

---

## Patient Attendance Analysis

The current filtered view contains:

- **316 delayed patients**
- **197 on-time patients**

This provides a view of patient attendance/processing status within the selected dashboard period.

---

## Demographic Analysis

### Gender Distribution

The current filtered view contains:

- **272 male patients**
- **241 female patients**

### Age Distribution

The current filtered view groups patients into eight age categories:

- 0–09
- 10–19
- 20–29
- 30–39
- 40–49
- 50–59
- 60–69
- 70–79

The **0–09 age group** has the highest patient count among the displayed age groups in the current filtered view.

---

## Department Referral Analysis

The current filtered view shows General Practice as the department with the highest number of recorded referrals, followed by Orthopedics.

The analysis also highlights records where no department referral was recorded.

This can help provide an overview of referral demand across hospital departments.

---

## Daily Trend Analysis

The Pivot Report includes daily analysis for:

- Number of patients
- Average patient waiting time
- Average patient satisfaction score

The dashboard currently displays the **January view through its month filter**, while the underlying dataset contains records from April 2023 through October 2024.

Daily patient volume helps identify fluctuations in emergency room demand.

Daily waiting-time analysis provides visibility into operational performance.

Daily satisfaction analysis provides an additional view of patient experience.

---

## Key Insights from the Current Dashboard View

The current filtered analysis provides several observations:

- The selected dashboard view contains **513 patients**.
- The average waiting time is **36.32 minutes**.
- The average satisfaction score is **4.96**.
- **269 patients were admitted**, representing approximately **52.44%** of the current filtered records.
- **244 patients were not admitted**, representing approximately **47.56%**.
- **316 patients were classified as delayed**, compared with **197 on time**.
- The current view contains slightly more male patients than female patients.
- The **0–09 age group** has the highest patient count among the displayed age groups.
- General Practice has the highest number of recorded department referrals.
- A substantial number of records in the current view have no department referral.
- Daily trends provide visibility into changes in patient volume, waiting time, and satisfaction.

These findings describe the **current filtered dashboard view**, not the complete 9,216-record dataset.

---

## Business Value

Hospital emergency departments need to monitor patient flow, waiting time, admissions, and patient experience.

This dashboard provides a consolidated analytical view that can help stakeholders:

- Monitor emergency department workload.
- Understand admission patterns.
- Identify delays.
- Track patient satisfaction.
- Understand demographic distributions.
- Review department referral patterns.
- Identify changes in daily patient demand.
- Support data-driven operational discussions.

---

## Skills Demonstrated

This project demonstrates practical experience with:

- Microsoft Excel
- Data Cleaning
- Data Organization
- Pivot Tables
- Data Aggregation
- KPI Development
- Percentage Calculations
- Date-Based Analysis
- Trend Analysis
- Demographic Analysis
- Dashboard Design
- Data Visualization
- Business Intelligence
- Git
- GitHub

---

## Tools & Technologies

### Microsoft Excel

Used for:

- Data analysis
- Pivot Tables
- Data aggregation
- Calculated metrics
- Filtering
- Trend analysis
- Dashboard development
- Data visualization

### CSV

Used as the raw data source for the project.

### Git & GitHub

Used for:

- Version control
- Portfolio management
- Project publishing
- Repository hosting

---

## Project Files

```text
Hospital Emergency Dashboard/
│
├── Final Dashboard of Hospital Emergency Analysis.png
├── Hospital Emergency Pivot Report.xlsx
├── Hospital Emergency Room Data.csv
├── Hospital_Logo.png
├── .gitignore
└── README.md
```

---

## File Descriptions

| File | Description |
|---|---|
| `Final Dashboard of Hospital Emergency Analysis.png` | Preview image of the completed Excel dashboard |
| `Hospital Emergency Pivot Report.xlsx` | Excel workbook containing the Pivot Report and Dashboard sheets |
| `Hospital Emergency Room Data.csv` | Raw emergency room patient dataset |
| `Hospital_Logo.png` | Hospital logo used in the dashboard |
| `.gitignore` | Git ignore rules for temporary Excel and OS files |
| `README.md` | Project documentation |

---

## Limitations

- The current dashboard screenshot represents a filtered January view rather than the complete dataset.
- The analysis is based on the fields available in the source dataset.
- The project does not include real-time hospital data.
- No predictive modeling or forecasting is included.
- The dashboard is developed in Microsoft Excel and requires Excel-compatible software for full interactive functionality.

---

## Future Improvements

Potential future improvements include:

- Add more interactive dashboard filters.
- Add year-over-year comparisons.
- Analyze peak emergency department periods.
- Add advanced KPI tracking.
- Build predictive models for patient volume and waiting time.
- Develop the dashboard in Power BI or Tableau.
- Connect the dashboard to a live database.
- Add automated data refresh capabilities.

---

## Project Outcome

This project demonstrates the complete process of transforming raw emergency room patient data into a structured Excel analytics solution.

It combines data organization, Pivot Table analysis, KPI development, filtering, demographic analysis, trend analysis, and dashboard visualization to provide a practical business intelligence view of emergency department activity.

The project also demonstrates the ability to distinguish between **dataset-level information** and **filtered dashboard-level insights**, ensuring that the reported metrics are interpreted correctly.

---

## Project Category

**Data Analytics | Business Intelligence | Microsoft Excel | Healthcare Analytics**

---

## Repository

urlHospital Emergency Dashboard GitHub Repositoryhttps://github.com/bhaskar-nb/hospital-emergency-dashboard

---

## Author

**Bhaskar**

Aspiring Data Analyst focused on SQL, Python, Excel, Tableau, Power BI, and Business Intelligence.

---

## Conclusion

The Hospital Emergency Room Analysis Dashboard provides a practical example of how Excel can be used to transform raw healthcare data into meaningful analytical insights.

The project highlights patient volume, admissions, waiting time, satisfaction, attendance, demographics, referrals, and daily trends through structured analysis and dashboard visualization.