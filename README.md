# Milan Area C and PM2.5 Concentrations

This repository contains the R code developed for a joint academic research project evaluating the impact of Milan’s Area C traffic policy on PM2.5 concentrations using a Regression Discontinuity in Time approach.

## Authors
Flavia Zavattarelli and Mariagiulia Villani

The project was jointly developed, with both authors involved in data preparation, programming, econometric analysis and interpretation of the results.

## Data
The analysis uses daily PM2.5 data for Milan covering the period 2008–2018, obtained from the Municipality of Milan, AMAT and ARPA Lombardia. Meteorological variables include temperature, wind speed, rainfall and humidity.

The raw datasets are not included in this repository. Their original institutional sources are identified in the accompanying research report.

## Methods and software
The analysis was conducted in R and includes:
- data import, cleaning and aggregation;
- integration of air-quality and meteorological data;
- data reshaping and visualisation;
- construction of time and treatment variables;
- Regression Discontinuity in Time estimation;
- robustness and diagnostic tests.

Main R packages: `readr`, `dplyr`, `tidyr`, `purrr`, `ggplot2` and `rdrobust`.

## Files
- `area_c_pm25_analysis.Rmd`: R code and empirical analysis.
- `Villani_Zavattarelli_Essay.pdf`: complete research report.



