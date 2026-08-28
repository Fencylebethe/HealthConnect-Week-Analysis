# HealthConnect Clinic – Week 4 Analysis

## AnalystLab Africa | Data Analytics Internship (Batch D)

This repository contains my Week 4 submission for the AnalystLab Africa Experience Lab, focused on the HealthConnect Clinic project: *Improving Patient Appointment Attendance and Healthcare Support Using Data and AI*.

## Project Background

HealthConnect Clinic is a fictional healthcare provider experiencing high rates of missed appointments (no-shows). This project explores how data and AI can help reduce no-shows and improve the patient support experience. Week 4 marks the foundation stage of a multi-week project that will progress through problem understanding, analysis and solution design, development, testing, and a final presentation.

## Week 4 Focus (Data Analytics Track)

Week 4 focused on understanding the appointment dataset and defining the foundation for analysis:
- Reviewed the dataset structure and Data Dictionary
- Conducted a data quality assessment (missing values, duplicates, category validity)
- Defined 3 business questions related to appointment no-shows
- Proposed 4 KPIs linked to those business questions
- Outlined an initial analysis approach and key assumptions/limitations/risks

## Files in This Repository

| File | Description |
|---|---|
| `HealthConnect_Week4_Analysis.docx` | Full Week 4 write-up: dataset overview, data quality assessment, business questions, KPIs, analysis approach, and assumptions/limitations/risks |
| `HealthConnect_Appointment_Data.xlsx` | Cleaned appointment dataset (converted from CSV) with data quality checks performed in Excel (missing value counts, duplicate check, category validation) |

## Key Findings (Data Quality)

- 5,000 appointment records, 18 variables
- No duplicate `appointment_id` values
- Missing values limited to `distance_to_clinic_km` (90) and `waiting_time_minutes` (60)
- Categorical fields (`appointment_outcome`, `appointment_type`) match the Data Dictionary exactly, with no inconsistencies

## Business Questions

1. Does booking lead time affect no-show rates?
2. Does a patient's previous no-show history predict future no-shows?
3. Do appointment type or time slot affect no-show rates?

## Next Steps (Week 5)

Calculate and visualise the proposed KPIs, and begin exploring relationships between multiple variables to identify the strongest predictors of no-shows.

## Author

Ofentse Lebethe — Data Analytics Intern, AnalystLab Africa (Batch D)
