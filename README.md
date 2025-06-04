# Analysis of Fertility Rates 

## Project Description
This repository contains the code for the capstone project of PSTAT 100 (Data Science Concepts & Analysis) at UCSB.  Students practice the data science lifecycle on a research topic of their choosing, exploring concepts such as inference, prediction, and notions of causality.

My project explores the decline in fertility rates across select developed nations in the 21st century and seeks to identify its key drivers. 

To this end, I conduct an in-depth analysis of gender, country, and world development indicators in Python, applying various data science techniques to address my research questions.  

## Background 
Over the last 50 years, the global fertility rate has halved. Modernization and technological advancements were coupled with a sharp decline in fertility as population growth surged. This growth was expected to plateau as fertility rates continued to fall. As of 2021, the global fertility rate is 1.66 and [falling](https://www.cbo.gov/publication/58912#:~:text=In%20CBO%27s%20projections%2C%20the%20total,where%20it%20remains%20through%202053). 

[Current research](https://ourworldindata.org/fertility-rate#data-sources) attribute this decline to factors such as women’s social mobility, economic stability, and improvements in child well-being.

This project seeks to explore:
* Which factors best predict a country’s fertility rate?
* How do upward mobility, economic prosperity, and child well-being impact fertility rates?
* Which of these explanations are the most probable?

## Data Sources
The data used in this project are sourced from
* [United Nations Development Programme](https://www.undp.org/) 
* [World Bank](https://data.worldbank.org/)
* Preprocessed datasets from [lab06](https://github.com/ucsb-ds/pstat100-content/tree/main/labs/lab6-regression/data). 

## Methods Used
* Preprocessing
    * Merging and indexing (via `pandas`) 
    * Missing values
    * Feature engineering: scaling (z-score), selection (via VIF) 
* Exploration
    * Correlation analysis (corrplots, heatmaps)
    * Feature analysis
        * Distribution analysis (scatterplots) 
    * Feature extraction (PCA) 
* Modeling
    * Multiple Regression Analysis 
* Diagnostics
    * Visualizations (Q-Q plots, residual plots)
    * Variance inflation factor (VIF) 

Python
* Analysis: `numpy`, `pandas`
* Modeling: `statsmodels` (PCA, OLS, stats), `scipy.stats`, `scikit-learn` 
* Visualization: `matplotlib`, `seaborn` 

*Revamped in June 2025 :) (original project 06-2023)*




