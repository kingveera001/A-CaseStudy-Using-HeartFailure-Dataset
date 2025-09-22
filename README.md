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

  
HeartDisease_Inferential_Analysis/
├── HeartDisease_analysis.ipynb       # Google Colab notebook with full implementation
├── HeartDisease_CaseStudy.xlsx       # Cleaned dataset + README sheet
├── HeartDisease_results.txt          # Statistical results for report/SPSS
├── HeartDisease_analysis_plots.png   # Visualizations (MaxHR and ChestPainType boxplots)
└── README.md                         # Project documentation
