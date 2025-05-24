# Analysis of Fertility Rates 

## Project Description
This repository contains the code for the capstone project of PSTAT 100 (Data Science Concepts & Analysis) at UCSB. Students practice the data science lifecycle on a research topic of their choosing, demonstrating key concepts such as inference, prediction, principles of measurement, and notions of causality.

My project explores the decline in fertility rates across select developed nations in the 21st century and seeks to identify its key drivers. To this end, I conduct an in-depth analysis of gender, country, and world development indicators in Python, applying various data science techniques to address my research questions.  

## Data Sources
The data used in this project are sourced from
* [United Nations Development Programme](https://www.undp.org/) 
* [World Bank](https://data.worldbank.org/)
* Preprocessed datasets from [lab06](https://github.com/ucsb-ds/pstat100-content/tree/main/labs/lab6-regression/data). 

## Project Roadmap
First, I preprocess the data by tidying datasets, extracting relevant variables, and handling missing values. Next, I perform exploratory data analysis (EDA), using statistical techniques to assess trends and variability. Then, I build and evaluate a multiple regression model, performing diagnostic tests to ensure valid analysis.

Multiple visualizations are created throughout for impact and clarity. The project concludes with a summary of key findings and recommendations for further analysis. 

## Methods Used
* Preprocessing
    * Data tidying, restructuring, and feature engineering
* EDA 
    * Feature analysis
    * Visualizations (scatterplots, histograms, heatmaps) 
    * Correlation analysis 
    * Principal component analysis (PCA)
* Modeling
    * Multiple Regression Analysis 
* Diagnostics
    * Q-Q plot (normality checks)
    * Residual plots
    * Variance inflation factor (VIF)

Python
* Analysis: `numpy`, `pandas`
* Modeling: `statsmodels` (PCA, OLS, stats), `scipy.stats`, `scikit-learn` 
* Visualization: `matplotlib`, `seaborn` 

*Revamped in May 2025 :) (original project 06-2023)*




