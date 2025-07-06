# COVID-19 Data Analysis

A comprehensive analysis of COVID-19 trends using Johns Hopkins CSSE data, examining global patterns, US state-level variations, and statistical correlations between case and death rates.

## Overview
This project analyzes COVID-19 data to answer key questions about pandemic trends, per-capita impacts across countries and US states, and correlations between case and death rates.

## Key Findings
- Exponential growth patterns in US cases and deaths
- Significant state-level variations in per-capita impacts
- Strong positive correlation (R² = X.XX) between case and death rates
- Identification of states that performed better/worse than predicted

## Data Sources
- Johns Hopkins CSSE COVID-19 Time Series Data
- Population lookup tables from the same repository

## Analysis Structure
1. Data import and cleaning
2. Transformation to tidy format
3. State and country-level aggregation
4. Visualization of trends and comparisons
5. Statistical modeling and correlation analysis

## Files
- [COVID19_data_analysis](COVID19_data_analysis.Rmd) - Main analysis notebook
- [Covid19_data_analysis.html](Covid19_data_analysis.html) - Knitted output
- [plots](plots) - Generated visualizations
- [Data source containg all csv files](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series) - Data documentation

## Requirements
- R 4.0+
- tidyverse, janitor, lubridate, ggplot2

## Usage
1. Clone the repository
2. Open [Covid19_data_analysis.Rmd](Covid19_data_analysis.Rmd) in RStudio
3. Run all chunks to reproduce the analysis


