# 721-Project-2
Repository created for project 2: air pollution data analysis

## Project Overview

This project processes and explores air pollution data from the RDU Airport monitoring station in North Carolina. It focuses on three pollutants: carbon monoxide (CO), particulate matter (PM2.5), and ozone (O3). The analysis summarizes daily concentrations and examines monthly and yearly patterns using tables and visualizations.

## Data Source

The data were obtained from the U.S. Environmental Protection Agency (EPA) air quality monitor at RDU Airport. Three datasets cover 2018, 2019, and January–April 2020.

## File Structure

- `Project2.Rmd` — RMarkdown file containing the data cleaning function, analysis, tables, and plots.
- `Project2.docx` — Final Word report generated from the RMarkdown file.
- `data/` — Original CSV datasets for 2018, 2019, and 2020.
- `.Rproj` — RStudio project configuration file.
- `README.md` — Project documentation.

## How to Reproduce

1. Clone or download this GitHub repository and open the RStudio project.
2. Install the required R packages: `tidyverse`, `here`, `gt`, `rmarkdown`, and `knitr`.
3. Open `Project2.Rmd` in RStudio.
4. Click **Knit** to run the analysis and generate the Word report (`Project2.docx`).

The RMarkdown file includes a function that cleans each year's data, calculates daily mean concentrations, and combines the datasets for further analysis.

## Author and Date

**Author:** Tianyuan Hou 
**Date:** November 14, 2026
