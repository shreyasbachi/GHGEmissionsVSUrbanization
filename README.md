# Analyzing Trends: Greenhouse Gas Emissions vs. Urbanization

## Description
This repository contains code for analyzing the relationship between greenhouse gas emissions and urbanization using data from the World Development Indicators. The analysis explores how urbanization trends correspond with changes in greenhouse gas emissions over time. It employs techniques such as data visualization, k-means clustering, and regression analysis to uncover patterns linking GHG emissions with the percentage of urban population.

## Getting Started

### Dependencies
- R and RStudio
- Required R packages:
  - `ggplot2` for data visualization
  - `dplyr` for data manipulation
  - `forecast` for forecasting models
  - `readr` for reading CSV data
  - `tidyr` for data tidying
  - `plotly` for interactive plots
  - `sf` for spatial data manipulation
  - `rnaturalearth` for map data
  - `viridis` for color palettes
  - `cluster` for clustering algorithms

### Setup
1. Install R and RStudio on your computer.
2. Open RStudio and install the required packages using the following commands:
   ```R
   install.packages(c("ggplot2", "dplyr", "forecast", "readr", "tidyr", "plotly", "sf", "rnaturalearth", "viridis", "cluster"))

### Dataset
The analysis is based on the World Development Indicators dataset, which can be downloaded from the World Bank website. Ensure to place the dataset in an accessible location and update the file path in the script accordingly.

### Running the Analysis
Open the R scripts in RStudio.
Adjust the file path to the dataset if necessary.
Execute the scripts sequentially to reproduce the analysis:
Data preprocessing
Data visualization
Regression analysis
Clustering analysis

### Project Structure
README.md: Project description and setup instructions.
Data analysis scripts: Contains all R scripts used for preprocessing, analysis, and visualization.
API_19_DS2_en_csv_v2_6542870.csv: Placeholder for the World Development Indicators dataset file path.
Data Source
This project uses the World Development Indicators dataset provided by the World Bank. Access the data here.

### Author
Shreyas Bachiraju

###Acknowledgments
Thanks to the World Bank for providing the comprehensive World Development Indicators dataset.
