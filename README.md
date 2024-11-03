# pymaceuticals

## Overview
This project analyzes and visualizes drug treatment data to evaluate the effectiveness of potential cancer treatments, particularly for squamous cell carcinoma (SCC). Using **Matplotlib**, plots and summaries are generated based on a 45-day animal study conducted by **Pymaceuticals, Inc.** 

## Features

### Data Preparation
- Merges the datasets and removes duplicates.
- Shows unique mouse counts before and after cleaning.

### Summary Statistics
- Calculates mean, median, variance, standard deviation, and SEM of tumor volume for each drug regimen.

### Bar Plots
- Show total observations for each drug regimen.
#### Drug Regimen vs. Number of Observed Timepoints
- Pandas Plot: Shows the total observations for each drug regimen using `pandas`.
- Matplotlib Plot: Same as above, but created with `matplotlib`.

### Pie Plots
#### Pie Plot - Percentage of Mice per Sex
- Pandas Plot: Visualizes the distribution of male and female mice using `pandas`.
- Matplotlib Plot: Same as above, but created with `matplotlib`.

### Quartile Analysis and Box Plot
- Calculates quartiles and identifies outliers for four promising treatments.
#### Box Plot - Drug Regimen vs. Tumor Volume
- Displays the distribution of final tumor volumes across four treatments (Capomulin, Ramicane, Infubinol, and Ceftamin), highlighting any outliers.

### Line Plot 
#### Tumor Volume over Time for Capomulin (Mouse y793)
- Tracks the tumor volume over time for a specific mouse treated with Capomulin to show the treatment's effect.

### Scatter Plot
#### Mouse Weight vs. Average Observed Tumor Volume (Capomulin)
- Visualizes the relationship between mouse weight and average tumor volume for mice treated with Capomulin.

### Correlation and Regression
- Calculates correlation and creates a linear regression model between weight and tumor volume.
#### Scatter Plot with Linear Regression Line - Mouse Weight vs. Average Tumor Volume (Capomulin)
- Similar to the scatter plot above, but includes a regression line to show correlation between mouse weight and tumor volume. Labels clarify the correlation's strength.

## Setup and Dependencies

To run this analysis, please ensure the following data files are in the `data/` folder: `Mouse_metadata.csv` & `Study_results.csv`. In addition, you will need Python 3 and the following libraries installed:

```python
# Dependencies
import matplotlib.pyplot as plt
import pandas as pd
import scipy.stats as st 
```

## Running the Analysis
- Clone the repository and navigate to the project directory.
- Install dependencies as shown above.
- Run the Jupyter Notebook or Python script to generate the analysis and visualizations