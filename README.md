# Research Project: Analysis of Fertility Rates 

## Project Description
This repository contains the code for the final capstone project of PSTAT 100 (Data Science Concepts & Analysis) at UCSB.  Students practice the data science lifecycle on a research topic of their choosing, demonstrating key course concepts such as inference and prediction, principles of measurement, missing data, and notions of causality.

My project examines the decline in fertility rates across select developed nations in 2018 and seeks to quantify the impact of gender, country, and world development indicators to total fertility rates. To achieve this, I will be conducting an in-depth analysis of fertility data in Python, applying various data science techniques to address my research questions.  

## Problem Statement
Over the last 50 years, the global fertility rate has halved. Modernization and technological advancements were coupled with a stark decline in fertility rates, while population growth surged. This rapid growth was expected to plateau as fertility rates – measured as the average number of children per woman – continued to decline. As of 2021, the global fertility rate is 1.66 and falling. 

Current perspectives attribute this decline to factors such as women’s social mobility, economic stability, and improvements in child well-being. This project seeks to explore the following questions:
* Which factors most predict a country’s fertility rate?
* How do upward mobility, economic prosperity, and child well-being impact fertility rates?
* Which of these explanations are the most probable?

## Data Sources
The data used in this project are sourced from
* [United Nations Development Programme](https://www.undp.org/) 
* [World Bank](https://data.worldbank.org/)
* Preprocessed datasets from [lab06](https://github.com/ucsb-ds/pstat100-content/tree/main/labs/lab6-regression/data). 

## Project Structure
The project is divided into two stages:
* Preparation and planning
    * Research: background information, data sources, and analytical objectives.
    * Clean and preprocess the data for analysis.
    * Deliverable: A brief interim report (2-4 pages) outlining the background, dataset, initial explorations, and at least 2 focused questions with possible approaches.
* Analysis and reporting
    * Perform exploratory analysis: examine variable distributions, correlations, and relationships using statistical techniques and visualizations.
    * Refine research questions based on findings.
    * Deliverable: A 3-5 page report summarizing the abstract, background, and methodology; key findings and analysis; a discussion of limitations and recommendations.

Note: The preparation and planning report will not be included in this repository. Due to scheduling conflicts, I've opted for an individual instead of group) project, resulting in a more comprehensive analysis. 

Detailed instructions are provided in the `project-description.ipynb` file. 

## Methods used
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
* Analysis: numpy, pandas, statsmodels (PCA, OLS, stats), scipy (stats), sklearn 
* Visualization: matplotlib, altair, seaborn








