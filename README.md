# NHANES Oral Health Disparities Dashboard

This repository contains my capstone health equity analytics project titled **Socioeconomic and Behavioral Determinants of Oral Health Outcomes Based on NHANES Data (2013–2018)**.

The project analyzes how income, education, smoking status, and dental insurance are associated with oral health outcomes among U.S. adults using NHANES data and Tableau visualization.

## Interactive Dashboard

[Open Tableau Dashboard](https://public.tableau.com/app/profile/vaishnavi.madhiraju6334/viz/NHANESOralHealthDisparitiesDashboard/Dashboard1)

## Project Overview

Oral health is an important part of overall well-being, but disparities persist across socioeconomic and behavioral groups. Lower income, limited education, smoking, and lack of dental insurance are associated with higher levels of untreated dental caries and tooth loss.

This project uses NHANES 2013–2018 data to analyze oral health disparities and generate evidence-based insights that can support public health interventions and oral-health equity.

## Objective

- Analyze how income, education, and smoking status influence oral health outcomes.
- Evaluate disparities in untreated dental caries and missing teeth among U.S. adults.
- Assess the role of dental insurance in oral health outcomes.
- Use regression analysis to identify significant predictors of poor oral health.
- Create an interactive Tableau dashboard to communicate findings.

## Dataset

- **Dataset:** National Health and Nutrition Examination Survey (NHANES)
- **Years Covered:** 2013–2018
- **Population:** U.S. adults aged 18 and older
- **Approximate Sample Size:** 25,000 adults
- **Source:** NHANES public-use data

## Variables

### Outcomes

- Untreated dental caries
- Missing teeth count

### Predictors

- Income-to-poverty ratio
- Education level
- Smoking status

### Confounders

- Age
- Sex
- Race/ethnicity
- Dental insurance status

## Tools Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Tableau
- NHANES public-use data

## Methodology

- Merged NHANES survey cycles from 2013–2014, 2015–2016, and 2017–2018.
- Cleaned and harmonized demographic, socioeconomic, behavioral, and oral health variables.
- Conducted descriptive and bivariate analyses.
- Applied logistic regression to model untreated dental caries.
- Applied linear regression to model missing teeth count.
- Created dashboard visualizations to communicate disparities and policy-relevant insights.

## Key Findings

- Untreated dental caries prevalence was higher among low-income adults compared to high-income adults.
- Missing teeth counts were higher among adults with lower education levels and current smokers.
- Lack of dental insurance was associated with more missing teeth.
- Smoking and poverty were among the strongest predictors of poor oral health outcomes.
- Income, education, and smoking collectively explained meaningful variation in oral health outcomes.

## Dashboard Highlights

The Tableau dashboard visualizes:

- Prevalence of untreated dental caries by income level
- Missing teeth patterns by education and smoking status
- Dental insurance-related differences in oral health outcomes
- Socioeconomic and behavioral predictors of oral health disparities
- Public health implications for prevention and equity-focused interventions

## Public Health Implications

Expanding preventive dental coverage, improving oral-health literacy, and integrating smoking cessation into community programs may help reduce disparities and promote oral-health equity among vulnerable populations.

## Repository Contents

- `CAPSTONE.pdf` - Capstone poster summarizing project background, methods, results, and conclusion
- `Dashboard 1.png` - Tableau dashboard screenshot
- `NHANES_Oral_Health_Disparities_Analysis.ipynb` - Python analysis notebook
- `README.md` - Project documentation

## Contributors

- Rithwik Raj Suram
- Vaishnavi Madhiraju
- Varshini Guthi

## Faculty Advisor

Dr. Divya S. Subramaniam  
Department of Health Data Science  
Saint Louis University

## Project Outcome

This project demonstrates a health equity analytics workflow using NHANES oral health data. The analysis combines socioeconomic, behavioral, and insurance-related factors to identify oral health disparities and support evidence-based public health recommendations.
