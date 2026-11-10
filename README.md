# Hospital Readmission Analytics Dashboard

## Project Overview
This project uses Power BI to analyze hospital encounter data and explore patterns in 30-day hospital readmissions. The dashboard examines readmission rates across patient age groups, previous inpatient visits, primary diagnosis codes, and length of hospital stay.

The goal is to use healthcare data visualization to identify patterns that may help support hospital quality improvement and healthcare decision-making.

## Tools Used

- Microsoft Power BI
- Healthcare Data Analysis
- Data Visualization
- Hospital Readmission Metrics

## Dashboard Preview

![Hospital Readmission Analytics Dashboard](dashboard-preview.png)

## Key Performance Indicators (KPIs)

| KPI | Dashboard Result | Description |
|---|---:|---|
| Total Encounters | 102K | Total hospital encounters displayed |
| Patient Number Count | 71.518K | Count of patient number records; not necessarily unique patients |
| Average Length of Stay | 4.40 days | Average time patients spent in the hospital |
| 30-Day Readmission Rate | 11.2% | Percentage reported by the dashboard's readmission measure |

## Dashboard Analysis

The dashboard includes the following visualizations:

- **30-Day Readmission Rate by Age:** Compares readmission rates with patient age groups.
- **30-Day Readmissions by Length of Stay:** Shows the number of readmissions for different hospital-stay durations.
- **30-Day Readmissions by Primary Diagnosis:** Compares readmission counts across primary diagnosis codes.
- **Patient Age by Length of Stay:** Displays the distribution of patient age records across hospital-stay durations.
- **30-Day Readmission Rate by Previous Inpatient Visits:** Examines how readmission rates vary with the number of previous inpatient visits.

## Key Findings

1. **Age and readmission patterns:** The 20–30 age group has the highest displayed 30-day readmission rate, at approximately 14%. The rates generally decline across the older age groups shown in the dashboard.

2. **Previous inpatient visits:** The dashboard suggests that readmission rates increase as the number of previous inpatient visits increases. This indicates a possible pattern between prior hospital use and subsequent readmissions. The smaller groups at higher visit counts should be interpreted carefully.

3. **Primary diagnosis:** Diagnosis code 428 has the highest displayed number of 30-day readmissions among the diagnosis codes shown. This is a count comparison, not a comparison of diagnosis-specific readmission rates.

## Limitations

- The visualizations show patterns and associations, not proof of cause and effect.
- Readmission counts and readmission rates represent different measures and should not be interpreted interchangeably.
- Groups with fewer patient records may produce less reliable percentages.
- The patient number count should not be interpreted as the number of unique patients unless a distinct-count calculation is used.

## Project Takeaway

This project strengthened my understanding of healthcare data analysis and Power BI visualization. It provided an opportunity to explore how patient age, previous inpatient visits, diagnosis codes, and hospital length of stay relate to hospital readmission patterns.
