# UAE Cancer Patient Insights Dashboard

[Introduction](#Introduction)

[Objective](#Objective)

[Story of Data](#StoryofData)

[Data Splitting and Preprocessing](#DataSplittingandPreprocessing)

[Pre-Analysis](#Pre-Analysi)

[In-Analysis](#In-Analysis)

[Post-Analysis and Insights](#Post-AnalysisandInsights)

[Data Visualizations & Charts](#DataVisualizations&Charts)

[Recommendations and Observations](#RecommendationsandObservations)

[Conclusion](#Conclusion)

[References & Appendices](#References&Appendices)

## Introduction
This report presents an analytical overview of cancer patient data from the United Arab Emirates. It provides insights on treatment timelines, cancer types, gender and age distributions, comorbidities, outcomes by treatment, and geographic patterns. The dashboard was created using Microsoft Excel to assist healthcare decision-makers, policymakers, and researchers in identifying high-risk groups, optimizing treatment strategies, and planning healthcare resources efficiently.

### Objective of the Project
To analyze cancer patient trends across various parameters including gender, cancer type, treatment outcomes, comorbidities, and Emirates-based distribution in the UAE. The goal is to derive insights that can support data-driven healthcare decisions.

Problem Being Addressed
Cancer remains a leading cause of mortality in the UAE. A structured view of patient demographics, treatment responses, and geographic distribution is needed to improve healthcare targeting and early interventions.

Key Datasets and Methodologies

Dataset sourced from public repositories (e.g., Kaggle).

Processed using Microsoft Excel (Pivot Tables, Charts, Conditional Formatting, Filters).

Focused on visual storytelling using dashboards for clarity.

3. Story of Data
Data Source: Kaggle (open healthcare dataset).
Collection Process: Scraped and consolidated from various cancer registries and anonymized health reports.
Data Structure: Rows = patient records; Columns = attributes like gender, age, cancer type, treatment, stage, Emirate, etc.
Key Features:

Cancer Type

Gender

Stage at Diagnosis

Treatment Type & Outcome

Age

Emirate Location

Comorbidities

Limitations:

Some underreporting for rare cancer types.

"Other" gender category may have limited data.

Time-based changes in data collection practices.

4. Data Splitting and Preprocessing
Data Cleaning: Removed duplicates, fixed missing values, standardized text formatting.
Handling Missing Values: Used Excel filters to isolate missing fields; defaulted to "Unknown" or interpolated where appropriate.
Transformations:

Grouped cancer types (Top 5).

Converted diagnosis dates into treatment delay (days).

Categorized age groups and stages.

Normalized treatment outcomes into 3 categories (Deceased, Recovered, Under Treatment).
Data Splitting:

Dependent: Outcome

Independent: Gender, Treatment Type, Cancer Type, Comorbidities, Stage
Industry Context: Healthcare – specifically oncology.
Stakeholders:

Ministry of Health

UAE Oncologists and Cancer Clinics

Health Policy Makers

Public Health Researchers
Value to Industry: Provides evidence-based insights for policy, treatment strategy refinement, resource allocation, and future research.

5. Pre-Analysis
Key Trends Identified:

Leukemia is the most common cancer type.

Females slightly more affected than males.

Hypertension is the most prevalent comorbidity.

Ajman has the highest number of reported cases.
Potential Correlations:

Higher stage = lower recovery rate.

Immunotherapy appears to yield the best recovery ratio.
Initial Insights:

There may be access or screening disparities between Emirates.

Early-stage detection improves recovery.

6. In-Analysis
Unconfirmed Insights:

Younger patients might respond better to certain treatment types.

Possible gender differences in cancer type prevalence.
Recommendations (Preliminary):

Increase screening and awareness in Ajman.

Expand access to immunotherapy where feasible.
Excel Techniques Used:

Pivot Tables for aggregating by type/gender/region

Data Bars & Conditional Formatting

Charts (bar, line, stacked columns)

Slicers for dynamic filtering

7. Post-Analysis and Insights
Key Findings:

Leukemia most common cancer.

Females are most affected.

Immunotherapy showed the highest recovery.

Ajman reports the highest case numbers.

Hypertension most frequent comorbidity.
Comparison with Expectations:

Ajman’s lead in cases was unexpected; further investigation needed.

Recovery rate differences by treatment type highlight the need for more personalized oncology approaches.

8. Data Visualizations & Charts
(a) Line Chart – Average Time from Diagnosis to Treatment
Shows treatment access lag per cancer type. Pancreatic cancer has the longest delay (~43,810 days).
(b) Stacked Column Chart – Cancer Stage by Outcome
Stage IV shows highest mortality. Stage I shows better recovery.
(c) Bar Chart – Top 5 Cancer Types
Leukemia leads with 1,314 patients.
(d) Bar Chart – Gender Distribution
Females (4,985) slightly higher than males (4,827); other genders minimally represented.
(e) Column Chart – Average Age by Cancer Type
Colorectal has the oldest average (54.3), Leukemia the youngest (52.4).
(f) Bar Chart – Cancer Cases by Emirate
Ajman (1,497) highest, Ras Al Khaimah (1,340) lowest among major Emirates.
(g) Bar Chart – Comorbidities
Hypertension most common (2,945), followed by diabetes and cardiovascular.
(h) Stacked Column Chart – Outcomes by Treatment Type
Immunotherapy yielded the most recoveries (1,256).
KPI Cards (Right Pane):
Summarize total cases, gender impact, most affected Emirate, top cancer, common comorbidity, and treatment effectiveness.

9. Recommendations and Observations
Actionable Insights:

Enhance awareness in Ajman and regions with high Stage IV diagnoses.

Expand use of immunotherapy and monitor its long-term effectiveness.

Focus interventions on comorbid patients, especially with hypertension.

Optimizations:

Introduce regional cancer screening programs.

Improve treatment lag for pancreatic and lung cancers.

Promote data collection for non-binary patients and rare cancers.

Unexpected Outcomes:

Nearly equal gender split challenges assumptions.

Some Emirates with better healthcare infrastructure still show high advanced-stage cases.

10. Conclusion
This analysis provides valuable insights into UAE cancer trends by patient demographics, geography, treatment, and outcomes. The findings support more targeted public health strategies and improved oncology practices.
Limitations:

Small sample sizes in less common cancer types.

Possible underreporting in comorbidity data.
Future Research:

Track survival over time.

Include socioeconomic and lifestyle variables.

11. References & Appendices
References:

Dataset from Kaggle (UAE Cancer Patient Dataset)

WHO cancer factsheets

UAE Ministry of Health statistics

Appendices:

Excel formulas used (VLOOKUP, COUNTIFS, SUMIFS)

Raw data sample screenshots

Additional charts not shown on the dashboard

Would you like this exported as a Word or PDF report format fo
