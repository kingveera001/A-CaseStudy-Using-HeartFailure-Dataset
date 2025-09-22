# Inferential Statistical Analysis of Cardiovascular Risk Markers

## Overview
This repository contains the implementation for the 21AIC401T Inferential Statistics and Predictive Analytics Case Study focused on cardiovascular risk markers using the Heart Disease dataset from Kaggle.

The analysis includes three statistical tests:

1. **One-sample t-test** → Cholesterol vs. 200 mg/dL
2. **Two-sample t-test** → MaxHR between male and female groups
3. **One-way ANOVA with Tukey HSD post-hoc** → MaxHR across ChestPainType categories

The project is implemented in Python (Google Colab), with outputs compatible for Excel and SPSS, meeting the requirements for the September 23, 2025 viva.

**Author:** R.M. Veerappan  
**Course:** 21AIC401T Inferential Statistics and Predictive Analytics  
**Date:** September 23, 2025

## Dataset
- Source: Kaggle Heart Disease Dataset (918 records)
- Variables: Age, Sex, ChestPainType, RestingBP, Cholesterol, FastingBS, RestingECG, MaxHR, ExerciseAngina, Oldpeak, ST_Slope, HeartDisease
- Cleaning: Missing values imputed with median where applicable
- link:https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction?resource=download

## Setup Instructions
1. Open Google Colab and create a new notebook named `Veerappan_analysis.ipynb`.  
2. Copy the Python code from this repo into the notebook.  
3. Run the cells in sequence — no manual dataset upload needed (dataset loaded locally as `heart_disease.csv`).  
4. Dependencies (`pandas`, `numpy`, `scipy`, `statsmodels`, `matplotlib`, `seaborn`) are pre-installed in Colab.  
5. The notebook auto-generates:  
   - `Veerappan_CaseStudy.xlsx` → cleaned data + variable descriptions  
   - `Veerappan_results.txt` → test results (t-statistics, p-values, CI)  
   - `HeartDisease_analysis_plots.png` → boxplots for MaxHR and ChestPainType

## Implementation Details

**Language:** Python 3 (Google Colab)  

### Tests Performed
- **One-sample t-test** → mean Cholesterol vs. 200 mg/dL (medical guideline threshold)  
- **Two-sample t-test** → MaxHR between Male and Female groups (Welch’s test)  
- **One-way ANOVA + Tukey HSD** → MaxHR across ChestPainType categories  

### Visualizations
- MaxHR boxplot by Sex  
- MaxHR boxplot by ChestPainType  

### Outputs
- **Excel file:** `HeartDisease_CaseStudy.xlsx` → cleaned dataset + variable descriptions  
- **Text file:** `HeartDisease_results.txt` → inferential test results (t-statistics, p-values, CI)  
- **Plots:** `HeartDisease_analysis_plots.png` → boxplots for inclusion in report  

---

## Usage

### Running the Notebook
1. Open `HeartDisease_analysis.ipynb` in Google Colab.  
2. Execute cells in order.  
3. No manual dataset upload needed — dataset is preloaded locally (`heart_disease.csv`).  
