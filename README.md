# smc_facility_surveillance_study
Reproducible R analysis for surveillance data including data cleaning, summary tables, and visualization of child health and bednet indicators.
# Surveillance Data Analysis

This repository contains an R Markdown workflow for cleaning, analyzing, and visualizing surveillance data related to children and bednet use.

The analysis focuses on summarizing key demographic indicators, sleeping space characteristics, and bednet utilization among children. The scripts produce summary tables and visualizations that support surveillance reporting and program monitoring.

## Repository Contents

- **surveillance_visuals.Rmd**  
  Main R Markdown script used for data cleaning, transformation, analysis, and visualization.

- **surveillance_visuals.html**  
  Rendered output of the R Markdown file containing tables and visualizations.

## Data Processing Steps

The analysis includes the following steps:

1. Importing surveillance data from Excel
2. Data cleaning and variable transformation
3. Creating age group categories
4. Renaming variables for analysis tables
5. Generating summary tables
6. Producing visualizations for key indicators

## Key Variables Analyzed

The analysis focuses on indicators such as:

- Child age groups
- Gender distribution
- Bednet availability in sleeping spaces
- Bednet use among children
- Sleeping space location
- Community health program awareness

## R Packages Used

The analysis uses several R packages including:

- `tidyverse`
- `dplyr`
- `ggplot2`
- `readxl`
- `lubridate`
- `janitor`
- `gtsummary`
- `gt`
- `arsenal`
- `flextable`
- `officer`
- `skimr`
- `writexl`

Package management is handled using the `pacman` package.

## Reproducibility

To reproduce the analysis:

1. Clone the repository
2. Install required R packages
3. Place the surveillance dataset in the specified working directory
4. Run the `surveillance_visuals.Rmd` file

## Author

Caroline Ngina

## Output

The final output is an HTML report that includes descriptive tables and visualizations summarizing surveillance indicators.
