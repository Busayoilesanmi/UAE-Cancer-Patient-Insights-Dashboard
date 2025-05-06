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

### Problem Being Addressed
Cancer remains a leading cause of mortality in the UAE. A structured view of patient demographics, treatment responses, and geographic distribution is needed to improve healthcare targeting and early interventions. This analysis seeks to know:

- What is the most common cancer type?
  
- What is the average age of patients by cancer type?
  
- Which emirate has the highest number of cases?
  
- What is the treatment duration (Diagnosis Treatment Start) by cancer type?
  
- What is the age group distribution of patients?
  
- What comorbidities are most common among cancer patients?
  
- What is the outcome by treatment type?
  
- How many deaths occurred per hospital?
  
- What’s the ethnicity by cancer type?
  
- What is the gender distribution across cancer types?

### Key Datasets and Methodologies

Dataset sourced from primary source ( Kaggle.com).

Processed using Microsoft Excel (Pivot Tables, Charts, Conditional Formatting, Filters).

Focused on visual storytelling using dashboards for clarity.

## Story of Data

### Data Source

Kaggle (open healthcare dataset).

### Collection Process

Scraped and consolidated from various cancer registries and anonymized health reports of the UAE

### Data Structure

Rows = patient records; Columns = attributes like gender, age, cancer type, treatment, stage, Emirate, etc.

### Key Features & Significance

* Cancer Type

* Gender

* Stage at Diagnosis

* Treatment Type & Outcome

* Age

* Emirate Location

* Comorbidities

### Limitations:

* Some underreporting for rare cancer types.

* "Other" gender category may have limited data.

* Time-based changes in data collection practices.

### Data Splitting and Preprocessing

### Data Cleaning 

* Removed duplicates

* Fixed missing values 

* Standardized text formatting.

### Handling Missing Values

Used Excel filters to isolate missing fields; defaulted to "Unknown" or interpolated where appropriate.

### Transformations

* Grouped cancer types (Top 5).

* Converted diagnosis dates into treatment delay (days).

* Categorized age groups and stages.

* Normalized treatment outcomes into 3 categories (Deceased, Recovered, Under Treatment).
  
### Data Splitting:

Dependent: Outcome

Independent: Gender, Treatment Type, Cancer Type, Comorbidities, Stage

### Industry Context
The healthcare industry in the United Arab Emirates (UAE) is rapidly evolving, with a strong emphasis on data-driven decision-making to improve patient outcomes and public health policies. Cancer remains one of the leading causes of morbidity and mortality in the region, and understanding its distribution, progression, and treatment efficacy is critical. As the UAE government invests in advanced medical infrastructure and national health registries, there is an increasing demand for insightful analytics that can guide cancer control strategies.

### Relevance of the Project to Analysis
This analytical project provides a deep dive into cancer patient data across multiple dimensions, including type, gender, age, comorbidities, stage of diagnosis, treatment methods, and regional distribution by emirate. Through Excel-based visualization and analytical methods, the project transforms raw patient data into meaningful insights that can assist healthcare professionals, policymakers, and researchers in understanding cancer trends within the UAE. It addresses key questions such as:

Which cancer types are most prevalent?

What are the demographics of affected patients?

How do treatment outcomes vary by stage and type?

Which emirates report higher case numbers?

### Stakeholders:

Ministry of Health

UAE Oncologists and Cancer Clinics

Health Policy Makers

Public Health Researchers

### Value to the Industry:
This analysis delivers significant value to the UAE healthcare industry in several ways:

* Targeted Intervention: By identifying high-risk groups (e.g., gender, age, region), healthcare providers can tailor early detection and screening programs.

* Resource Allocation: Emirates with higher case loads can be prioritized for medical resources, personnel, and awareness campaigns.

* Treatment Optimization: Understanding which treatments yield better outcomes allows for evidence-based adjustments in clinical practice.

* Policy Development: Data-driven insights enable government bodies to formulate more effective cancer control policies and allocate funding based on actual needs.

* Public Health Awareness: The dashboard simplifies complex health data, making it accessible for public education and community outreach.

* It Provides evidence-based insights for policy, treatment strategy refinement, resource allocation, and future research.

## Pre-Analysis

### Key Trends Identified:

* Leukemia is the most common cancer type.

* Females slightly more affected than males.

* Hypertension is the most prevalent comorbidity.

* Ajman has the highest number of reported cases.
  
### Potential Correlations:

* Higher stage = lower recovery rate.

* Immunotherapy appears to yield the best recovery ratio.
  
## Initial Insights:

* There may be access or screening disparities between Emirates.

* Early-stage detection improves recovery.

## In-Analysis

### Unconfirmed Insights:

* Younger patients might respond better to certain treatment types.

* Possible gender differences in cancer type prevalence.
  
### Recommendations

* Increase screening and awareness in Ajman.

* Expand access to immunotherapy where feasible.
  
### Excel Techniques Used:

* Pivot Tables for aggregating by type/gender/region

* Data Bars & Conditional Formatting

* Charts (bar, line, stacked columns)

* Slicers for dynamic filtering

## Post-Analysis and Insights

### Key Findings:

* Leukemia most common cancer.

* Females are most affected.

* Immunotherapy showed the highest recovery.

* Ajman reports the highest case numbers.

* Hypertension most frequent comorbidity.
  
### Comparison with Expectations:

* Ajman’s lead in cases was unexpected; further investigation needed.

* Recovery rate differences by treatment type highlight the need for more personalized oncology approaches.

## Data Visualizations & Charts

![Dashboard7](https://github.com/user-attachments/assets/286ec98d-2c65-4fe6-933d-0f7c29119e0c)

### Link to the Excel documents and Dashboard

https://docs.google.com/spreadsheets/d/1WbTab1zCmW2PkS6LdqZcMFTQ5vUG1JrM/edit?usp=drive_link&ouid=104478848167416604596&rtpof=true&sd=true

#### Dashboard Explanations:

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

## Recommendations and Observations

### Actionable Insights:

* Enhance awareness in Ajman and regions with high Stage IV diagnoses.

* Expand use of immunotherapy and monitor its long-term effectiveness.

* Focus interventions on comorbid patients, especially with hypertension.

### Optimizations:

* Introduce regional cancer screening programs.

* Improve treatment lag for pancreatic and lung cancers.

* Promote data collection for non-binary patients and rare cancers.

### Unexpected Outcomes:

* Nearly equal gender split challenges assumptions.

* Some Emirates with better healthcare infrastructure still show high advanced-stage cases.

## Conclusion
This analysis provides valuable insights into UAE cancer trends by patient demographics, geography, treatment, and outcomes. The findings support more targeted public health strategies and improved oncology practices.

### Limitations:

- Small sample sizes in less common cancer types.

- Possible underreporting in comorbidity data.
  
### Future Research:

Track survival over time.

Include socioeconomic and lifestyle variables.

## References & Appendices

### References:

Dataset from Kaggle: ([UAE Cancer Patient Dataset](https://www.kaggle.com/datasets/ak0212/uae-cancer-patient-dataset))

Microsoft Excel Documentation: https://docs.google.com/spreadsheets/d/1WbTab1zCmW2PkS6LdqZcMFTQ5vUG1JrM/edit?usp=drive_link&ouid=104478848167416604596&rtpof=true&sd=true

Screenshot: https://drive.google.com/file/d/1c-LhxqlB_YU8Tliq-kEkEIC6FtPTFYX3/view?usp=drive_link

### Appendices:

* Appendix A: Full Pivot Table Output

* Appendix B: Excel Formulas Used

* Appendix C: Raw Dataset (sanitized)

* Appendix D: Screenshot of Final Dashboard

