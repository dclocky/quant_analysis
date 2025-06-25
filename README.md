# Quantitative Analysis of the Irish Housing Market and Birthrates

This repository contains material for a Data Science project exploring the relationship between housing affordability and fertility trends in Ireland from 2010 to 2023. The work combines publicly available datasets from the Central Statistics Office (CSO) and analyses them using Python, Jupyter Notebook and Bayesian modelling techniques.

## Contents

- `Daryn_Loughlin_Quant_Analysis.ipynb` – Jupyter Notebook with all data preparation, exploratory plots and the Bayesian logistic regression model.
- `Analysis Report` – A text document summarising the project background, methodology and key findings.

## Getting Started

1. Clone this repository.
2. Install Python 3 and the required libraries. The notebook uses common packages such as `pandas`, `numpy`, `matplotlib`, `seaborn`, `statsmodels`, `pymc`, and `arviz`.
   ```bash
   pip install pandas numpy matplotlib seaborn statsmodels pymc arviz pyjstat requests
   ```
3. Open `Daryn_Loughlin_Quant_Analysis.ipynb` in Jupyter and run the cells sequentially. The notebook downloads the necessary CSO data, cleans it, and fits the Bayesian model.
4. Consult the `Analysis Report` for an overview of the results and conclusions.

## Project Summary

The analysis investigates whether rising housing costs and general living expenses are linked with the decline in birth rates in Ireland. A Bayesian logistic regression model estimates the probability of a year having a low birth rate given high housing and cost-of-living burdens. Results indicate a significant association between affordability pressures and reduced fertility outcomes.

## License

This project is made available for educational purposes. All data used comes from publicly accessible CSO datasets.
