# 🏥 Healthcare Patient Analysis Dashboard

## Overview
An Excel-based analytics dashboard built from a 10,000-patient dataset. It uses PivotTables, PivotCharts, and summary KPI cells to surface patient demographics, admission patterns, and treatment outcomes — all within a single workbook.

---

## File Structure (actual)
The workbook `Healthcare_Patient_Analysis_Dashboard.xlsx` contains 8 sheets:

| Sheet | Contents |
|---|---|
| `Dashboard` | Main visual dashboard — KPI cards and charts |
| `KPI` | Summary KPI values (see below) |
| `healthcare_patients` | Raw data: 10,000 patient records, 19 columns |
| `Patients by Diagnosis` | Pivot table — patient count by diagnosis |
| `Patients by Admission Type` | Pivot table — patient count by admission type |
| `Gender Distribution` | Pivot table — patient count by gender |
| `Readmission` | Pivot table — 30-day readmission counts |
| `BMI Category` | Pivot table — patient count by BMI category |

---

## KPIs Calculated
- **Total Patients:** 10,000
- **Average Age:** 64.8 years
- **Average BMI:** 27.5
- **Average Treatment Cost:** $14,530.79
- **Average Length of Stay:** 7.3 days
- **Readmission Count:** 1,202
- **Readmission Rate:** 12.02%

---

## Raw Data Columns (`healthcare_patients` sheet)
`patient_age`, `gender`, `bmi`, `systolic_bp`, `diastolic_bp`, `cholesterol_mg_dl`, `fasting_blood_sugar`, `heart_rate_bpm`, `previous_admissions`, `admission_type`, `primary_diagnosis`, `medication_adherence`, `length_of_stay_days`, `treatment_cost_usd`, `readmission_30_days`, plus derived fields: `Age_Group`, `BMI_Category`, `Blood Pressure Status`, `Cost Category`

---

## Dashboard Features
- KPI summary cards (patients, age, BMI, cost, length of stay, readmission rate)
- Diagnosis breakdown (Cardiology, Endocrinology, Orthopedics, Respiratory)
- Admission type breakdown (Elective, Emergency, Urgent)
- Gender distribution
- BMI category distribution (Normal, Overweight, Obese, Underweight)
- 30-day readmission tracking

---

## Tools Used
- Microsoft Excel
- PivotTables & PivotCharts
- Excel formulas (KPI aggregation)

*(Note: there is no `.pbix`, SQL database, or Power Query/DAX model in this file — it's a self-contained Excel workbook, not a Power BI project.)*

---

## Business Insights
- Cardiology is the leading diagnosis category (3,491 of 10,000 patients)
- Emergency admissions are the most common admission type (3,925 patients)
- Gender split is nearly even (50.2% Female / 49.8% Male)
- ~12% of patients are readmitted within 30 days
- Overweight and Obese categories together make up the majority of BMI classifications

---

## Skills Demonstrated
- Dashboard design in Excel
- PivotTable & PivotChart construction
- KPI calculation and summary reporting
- Data cleaning and categorization (Age_Group, BMI_Category, Cost Category, etc.)

---

## Author
**Rakshitha S**
Data Analyst
