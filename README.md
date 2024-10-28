# pymaceuticals

## Overview
This project analyzes and visualizes drug treatment data to evaluate the effectiveness of potential cancer treatments, particularly for squamous cell carcinoma (SCC). Using **Matplotlib**, plots and summaries are generated based on a 45-day animal study conducted by **Pymaceuticals, Inc.** 

## Features

### Data Preparation
- Merges the datasets and removes duplicates.
- Shows unique mouse counts before and after cleaning.

### Summary Statistics
- Calculates mean, median, variance, standard deviation, and SEM of tumor volume for each drug regimen.

### Bar and Pie Charts
- **Bar Charts**: Show total data points for each drug regimen.
- **Pie Charts**: Display gender distribution of mice in the study.

### Quartile Analysis and Box Plot
- Calculates quartiles and identifies outliers for four promising treatments.
- Displays tumor volume distributions with a **box plot**.

### Line Plot and Scatter Plot
- **Line Plot**: Tracks tumor volume over time for a selected mouse.
- **Scatter Plot**: Shows correlation between mouse weight and tumor volume for Capomulin treatment.

### Correlation and Regression
- Calculates correlation and creates a linear regression model between weight and tumor volume.