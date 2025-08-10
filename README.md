# Forecasting Daily Bike Rental Demand

## Overview
This project analyzes and forecasts daily bike rental demand using time series models in R.  
The analysis includes exploratory data analysis (EDA), seasonal decomposition, and ARIMA modeling.

## Files in this Repository
- `bike_share.Rmd` – Main R Markdown file containing the analysis, code, and conclusions.
- `bike_share.html` – Rendered HTML report from the R Markdown file.
- `data/` – Folder containing the dataset(s) used in the analysis.
- `README.md` – Project description and instructions.

## Data Source
The dataset comes from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/),  
specifically the Bike Sharing Dataset, which records daily bike rental counts and related features.

## Methodology
1. **Data Cleaning & Preparation**  
   - Converted date fields to proper formats.
   - Removed missing or inconsistent values.
2. **Exploratory Data Analysis**  
   - Trends, seasonality, and correlation analysis.
3. **Modeling**  
   - Auto ARIMA model selection.
   - Residual diagnostics.
4. **Forecasting**  
   - 30-day demand forecast with confidence intervals.

## Results & Findings
- The ARIMA(1,1,1) model provided the best fit based on AIC and residual analysis.
- Seasonality and temperature were strong predictors of rental demand.
- The forecast shows expected demand peaks on weekends and during warmer days.

## Requirements
- R (version 4.0 or later)
- R packages: `tidyverse`, `forecast`, `lubridate`, `ggplot2`

## How to Reproduce
1. Clone this repository:
   ```bash
   git clone https://github.com/KwameSA/bike-share-forecast.git
2. Open bike_share.Rmd in RStudio.
3. Knit the document to HTML to run all code and reproduce results.

## View Output
- [Click here to view output]()

Author
[Samuel Akuffo](https://kwamesa.github.io/portfolio/index.html)
