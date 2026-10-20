# Hospital 30-Day Readmission Risk Analysis

## Project Overview

Hospital readmissions within 30 days of discharge can increase healthcare costs, occupy hospital beds, and add to staff workloads. They may also highlight opportunities to improve discharge planning and follow-up care.

This project analyzes a synthetic dataset of 500,000 hospital patient records, generated using Claude AI, to investigate factors associated with 30-day hospital readmission.

Using Python, the project combines data cleaning, exploratory data analysis, statistical hypothesis testing, and logistic regression to examine readmission patterns and evaluate how well the model distinguishes between readmitted and non-readmitted patients.

## Full Project Report

[View Full Hospital Readmission Analysis Report (PDF)](Hospital_30-Day_Readmission_Risk_Analysis_Report.pdf)


## Project Objectives

- Assess and clean the dataset.
- Handle missing values using appropriate imputation methods.
- Examine patient characteristics and readmission patterns.
- Test associations between patient and admission characteristics and 30-day readmission.
- Apply logistic regression and evaluate its classification performance.
- Communicate findings and acknowledge analytical limitations.

## Dataset Overview

The synthetic dataset contains 500,000 patient records and includes the following 13 factors:

- Age
- Gender
- Race
- Admission type
- Length of stay
- Primary diagnosis
- Previous admissions
- Number of medications
- Comorbidity count
- Discharge disposition
- Haemoglobin level
- Creatinine level
- Insurance type

## Tools and Technologies

- Python
- Pandas
- Statistical hypothesis testing
- Logistic regression
- Model evaluation
- Data visualization

## Statistical Methods

The analysis used:

- Descriptive statistics
- Chi-square tests
- Independent-samples t-tests
- Mann–Whitney U test
- Logistic regression
- ROC-AUC for model evaluation

## Key Findings

### 1. Overall Readmission Rate

A total of 145,413 patients were readmitted within 30 days, representing 29.08% of the dataset.

### 2. Factors Associated with Readmission

Age, admission type, length of stay, primary diagnosis, previous admissions, comorbidity count, number of medications, and discharge disposition showed statistically significant associations with readmission.

Gender, race, haemoglobin level, creatinine level, and insurance type did not show statistically significant associations in the reported analyses.

### 3. Age and Readmission

Readmission rates increased from 18.34% among patients aged 18–24 to 31.83% among patients aged 65 and above.

### 4. Logistic Regression Performance

The logistic regression model achieved an ROC-AUC of 0.55, indicating limited ability to distinguish between patients who were readmitted and those who were not.

Although several variables showed statistically significant associations with readmission, the large sample size means statistical significance should not be confused with practical importance.

## Limitations

- The dataset is synthetic and does not represent actual patient records.
- The findings demonstrate analytical methods rather than real-world clinical outcomes.
- Associations do not establish causation.
- The model's ROC-AUC of 0.55 indicates weak discrimination and limits its usefulness as a predictive model.

## Project Report

The full project report will be available in this repository.

## Conclusion

This project demonstrates a healthcare data analytics workflow involving data cleaning, missing-value imputation, exploratory analysis, statistical hypothesis testing, and logistic regression evaluation.

The results highlight the importance of assessing both statistical significance and model performance when analyzing healthcare data.
