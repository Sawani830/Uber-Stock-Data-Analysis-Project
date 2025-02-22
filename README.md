# Uber Stock Data Analysis Project

This repository contains a comprehensive data analysis project in R using Uber's stock market data. The analysis includes data cleaning, exploratory data analysis (EDA), visualization, time series decomposition, and forecasting.

## Dataset

The dataset `uber_stock_data.csv` contains daily stock information for Uber, including:
- Date
- Adjusted Close Price
- Close Price
- High Price
- Low Price
- Open Price
- Volume

## Files

- `uber_stock_analysis.R`: The R script containing all analysis steps.
- `uber_stock_data.csv`: Dataset file used for analysis.

## Analysis Steps

### 1. Data Import and Cleaning
- Imported data using `read_csv()`.
- Converted `Date` column to Date type.
- Checked for and handled missing values.

### 2. Exploratory Data Analysis (EDA)
- Summarized data statistics.
- Visualized closing price trends over time.
- Created histograms and boxplots for price distribution analysis.

### 3. Time Series Analysis
- Converted data to a time series object.
- Decomposed time series to identify trends, seasonality, and residuals.

### 4. Forecasting
- Built an ARIMA model using `auto.arima()`.
- Forecasted the next 30 days of closing prices.
- Visualized the forecast results.

## Requirements

Install necessary R packages:
```R
install.packages(c("readr", "dplyr", "ggplot2", "lubridate", "forecast"))
```

## Usage

Run the analysis by sourcing the R script:
```R
source('uber_stock_analysis.R')
```

## Results
- Plots showing stock price trends and distributions.
- ARIMA model summary and forecast visualization.



