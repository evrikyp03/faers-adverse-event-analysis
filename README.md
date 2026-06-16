# FAERS Pharmacovigilance Analysis

## Overview
Analysis of FAERS (FDA Adverse Event Reporting System) data to identify patterns in drug–reaction relationships and severity outcomes using Python, SQL, and Power BI.

---

## Dashboard Preview
<img width="1282" height="722" alt="FAERS_DASHBOARD_ALL" src="https://github.com/user-attachments/assets/0b14e633-ac60-433e-91a0-2544527298cb" />


---

## Objectives
- Identify patterns in adverse drug reactions  
- Engineer severity scores from clinical outcome flags  
- Rank drugs by reported severity burden  
- Compare severity across drugs and age groups  
- Build an interactive Power BI dashboard for exploration  

---

## Dataset
FAERS reports including:
- Suspect drug information  
- Reactions and outcomes  
- Patient demographics  
- Severity indicators (fatal, hospitalized, life-threatening)  

---

## Tools
- Python — data cleaning & feature engineering  
- SQL — aggregation & ranking  
- Power BI — interactive visualization  

---

## Methodology

### Data Preparation
- Selected relevant clinical and outcome variables  
- Cleaned and standardized reporting fields  

### Severity Engineering
- Combined outcome flags into a unified severity framework  
- Enabled cross-drug severity comparison  

### Analysis
- Explored drug–reaction clustering patterns  
- Ranked drugs by severity score  
- Examined demographic variation in outcomes  

### Dashboard
- KPI summary of adverse outcomes  
- Severity distribution overview  
- Drug-level and age-group comparisons  

---

## Python Notebook

The exploratory analysis and feature engineering were performed in a Jupyter Notebook. This includes:
- Data cleaning and preprocessing
- Creation of severity score from outcome flags
- Initial exploratory analysis of drug–reaction patterns

The full analysis workflow is available in the Jupyter notebook included in this repository.

---

## Key Insights
- Most reports are non-fatal; hospitalization dominates severe outcomes  
- Fatal events are rare but non-negligible  
- Severity patterns vary significantly across drugs  
- Reporting data reflects bias and population risk factors, not causality  

---

## Limitations
- Spontaneous reporting system (not incidence data)  
- Reporting and selection bias  
- Incomplete clinical context  

---

## Project Structure
faers-pharmacovigilance-analysis/

│

├── faers_exploration.ipynb

├── FAERSPBI.pbix

├── FAERS_DASHBOARD_ALL.png

└── README.md

---

## Summary
End-to-end analytics pipeline combining Python, SQL, and Power BI to explore adverse drug event severity patterns in FAERS data.
