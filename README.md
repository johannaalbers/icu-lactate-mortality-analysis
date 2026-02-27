- # ICU Mortality and Early Lactate Levels  
### Retrospective Cohort Study using MIMIC-III

---

## Project Overview

Are elevated lactate levels within the first 24 hours of ICU admission associated with in-hospital mortality?

This project investigates the prognostic value of early lactate measurements using real-world ICU data from the MIMIC-III clinical database.

---

## Data Source

- MIMIC-III v1.4 critical care database  
- Adult ICU stays  
- Lactate measurements within the first 24 hours of ICU admission  

Cohort characteristics:

- 21,016 unique subjects  
- 25,743 ICU stays  
- 128,715 lactate observations  

---

## Study Design

- Retrospective cohort study  
- Exposure: first lactate measurement within 24 hours  
- Outcome: in-hospital mortality  
- Statistical method: logistic regression  
- Model performance evaluated using ROC curve and AUC  

---

## Data Processing

- Cohort construction via SQL (CTEs & window functions)  
- Cleaning of non-numeric and extreme lactate values  
- Manual correction of mortality flag inconsistencies  
- Missing data analysis and visualization  
- Log-transformation for distribution analysis  

---

## Exploratory Data Analysis

- Distribution of lactate values (log-scale)  
- Missing value patterns  
- Mortality distribution across lactate strata  

Higher lactate levels were associated with increased mortality rates.

---

## Statistical Analysis

- Logistic regression modeling  
- Odds ratio interpretation  
- ROC curve analysis for discrimination performance  
- Subgroup and sensitivity analyses  

---

## My Contribution

This project was originally developed as part of a collaborative academic assignment.

My individual contributions include:

- data cleaning implementation  
- Full exploratory data analysis  
- Implementation and documentation of statistical modeling
- Scientific writing: introduction, biological background, methods (excluding ML section), results, discussion, and conclusion  

Other team members contributed to cohort construction, missing data analysis, and machine learning extensions.

---

## Reproducibility

- SQL extraction scripts included  
- R scripts for cleaning, EDA, and statistical modeling  
- Access to MIMIC-III required  

---

## Skills Demonstrated

- Clinical cohort definition  
- SQL (joins, window functions, CTEs)  
- Data cleaning and validation  
- Missing data analysis  
- Logistic regression modeling  
- ROC/AUC interpretation  
- Scientific reporting  

---

## Disclaimer

The MIMIC-III dataset requires credentialed access.  
No patient-level data is included in this repository.
