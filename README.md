1.Hospital Patients Data — Analytics Dashboard

An interactive Power BI dashboard built to analyze hospital patient data — exploring procedure costs, length of stay, readmission rates, patient satisfaction, and gender distribution across thousands of hospital visits.


2.Purpose

Hospital administrators and healthcare analysts often struggle to extract actionable insights from large, unstructured patient records. This dashboard addresses that gap by visualizing key operational and clinical metrics — helping identify high-cost procedures, readmission patterns, and satisfaction trends.


2.Tech Stack

| Tool | Usage |
|------|-------|
| Power BI Desktop | Main visualization platform |
| Power Query | Data cleaning & transformation |
| DAX | Calculated measures & KPIs |MS Exel |
| Data Modeling | Table relationships & aggregations |
| Development & preview formats |


3.Data Source

**Kaggle — Hospital Patients Dataset**  
A publicly available dataset containing patient demographics, procedures, treatment costs, length of stay, readmission status, and satisfaction scores.


4.Key KPIs

| Metric | Value |
|--------|-------|
| Total Records | 492K |
| Unique Patients | 6K |
| Female Patients | 53.25% |
| No Readmission | 73.17% |
| Peak Satisfaction Score | 4 (458 patients) |
| Top Procedure Cost | ~1.65M |


5.Key Visuals

- **Gender Distribution** — Pie chart: 53.25% female vs 46.75% male
- **Cost by Procedure** — Column chart ranking procedures by total cost (Surgery leads at ~1.65M)
- **Readmission Rate** — Donut chart: 73.17% not readmitted vs 26.83% readmitted
- **Length of Stay** — Horizontal bar chart showing minimum stay per procedure
- **Satisfaction Score** — Area + line chart peaking at score 4 with 458 patients
- **Gender Filter** — Interactive slicer to segment all visuals by gender


6.Business Impact & Insights

- **Cost management:** Surgical and radiation procedures are the costliest — useful for budget prioritization
- **Readmission reduction:** 26.83% readmission rate helps identify high-risk procedures for better post-discharge care
- **Operational planning:** Length of stay data supports bed availability and resource scheduling
- **Patient experience:** Satisfaction peaks at 4/5 — actionable for quality improvement initiatives


7.Dashboard Preview

Hospital Patients Dashboard 
Example: ![Dashboard Preview](https://github.com/Adityapawar1117/Bi-Hospital-dashboard-/blob/main/Hospital%20dashboard%20Snapshot.png)
