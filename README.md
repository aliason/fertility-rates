# Research Project: Analysis of Fertility Rates 

## Project Description
This repository contains the code for the capstone project of PSTAT 100 (Data Science Concepts & Analysis) at UCSB.  Students practice the data science lifecycle on a research topic of their choosing, demonstrating key course concepts such as inference and prediction, principles of measurement, missing data, and notions of causality.
 
My project investigates the decline in fertility rates across select developed nations in the 20th century and seeks to identify key drivers of this decrease. To this end, I will conduct an in-depth analysis of gender, country, and socioeconomic indicators in Python, applying various techniques to address my research questions.  

## Problem Statement
Over the last 50 years, the global fertility rate has halved. Modernization and technological advancements were coupled with a stark decline in fertility rates, while population growth surged. This rapid growth was expected to plateau as fertility rates – measured as the average number of children per woman – continued to decline. As of 2021, the global fertility rate is 1.66 and falling. 

Current perspectives attribute this decline to factors such as women’s social mobility, economic stability, and improvements in child well-being. This project seeks to explore:
* Which factors most predict a country’s fertility rate?
* How do upward mobility, economic prosperity, and child well-being impact fertility rates?
* Which of these explanations are the most probable?

## Data Sources
The data used in this project are sourced from
* [United Nations Development Programme](https://www.undp.org/) 
* [World Bank](https://data.worldbank.org/)
* Preprocessed datasets from [lab06](https://github.com/ucsb-ds/pstat100-content/tree/main/labs/lab6-regression/data). 

## Methods Used
* Data processing
    * Data tidying, restructuring, and feature engineering
* Exploratory data analysis (EDA)
    * Feature analysis
    * Data visualization (scatterplots, histograms, heatmaps) 
    * Correlation analysis 
    * Principal component analysis (PCA)
* Data modeling
    * Multiple Regression Analysis 
* Model diagnostics
    * Q-Q plot (normality check)
    * Residual plot
    * Variance inflation factor (VIF)

Python
* Data analysis: `numpy`, `pandas`
* Statistical modeling: `statsmodels` (PCA, OLS, stats), `scipy.stats`, `scikit-learn` 
* Visualization: `matplotlib`, `altair` 


## Visualizing the Results 
Note: GitHub does not fully support interactive Altair charts in Jupyter notebooks, so visualizations may not display correctly in the `.ipynb` file.

View the fully rendered interactive notebook [here](final-project/project-final.html)






