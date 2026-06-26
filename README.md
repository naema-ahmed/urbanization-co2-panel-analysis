# Urbanization & CO₂ Panel Data Analysis
A collaborative university project in statistical learning investigating the relationship between urbanization and CO₂ emissions using panel data regression techniques (including Pooled OLS and Fixed Effects models) in Python. 

## Overview

This project examines whether increasing urbanization is associated with changes in CO₂ emissions across countries. The dataset described the CO₂ emissions per capita, population, energy consumption, GDP, and their related indexes and growth/lagged variables for 36 countries across a 28-year period (1975-2002). Multiple econometric models were implemented and compared, including linear and quadratic Pooled OLS regression, and Fixed Effects models, with robustness checks to validate the findings.

## Methodology

* Data preprocessing (feature engineering & dataset indexing)
* Exploratory data analysis
* Linear and Quadratic Pooled OLS regression
* Country and Time Fixed Effects models (entity, time, & entity-time effects)
* Variable selection (AIC, BIC, R^2, etc)
* Robustness checks (First Difference, log specification, lagged variables)
* Heterogeneity analysis by GDP and population
* Model diagnostics including multicollinearity, heteroskedasticity, and residual analysis

## Key Findings

* Pooled OLS models suggest the presence of a statistically significant relationship between 
urbanization and CO₂ emissions, with evidence of nonlinearity and an inverted U-shaped turning point in 
the quadratic specification.
* After controlling for both country and time fixed effects, urbanization was no longer a statistically significant predictor.
* Energy consumption consistently remained a positive and highly statistically significant predictor of CO₂ emissions across all model specifications.
* Robustness checks supported the conclusion that the apparent relationship in pooled models was primarily driven by differences between countries rather than changes within countries over time.

## Technologies

* Python (Jupyter Notebook), pandas, NumPy, statsmodels, linearmodels, matplotlib, scikit-learn

## Repository Contents

* `notebook.ipynb` – Complete analysis and model implementation
* `report.pdf` – Final project report

