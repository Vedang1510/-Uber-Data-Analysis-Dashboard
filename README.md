# Uber Data Analysis Dashboard

This repository contains R code for analyzing Uber data and creating an interactive dashboard using R Markdown and the `flexdashboard` package. The dashboard provides visualizations and insights into various aspects of Uber trips, including trips by hour, trips by month, trips by day of the week, and more.

## Overview

The analysis includes data from multiple months, which are combined and preprocessed to extract useful information such as date, time, month, day of the week, etc. The dashboard presents these insights through different types of graphs, including bar plots, scatter plots, box plots, pie charts, and histograms.

## Features

- **Bar Graph**: Visualizes trips by hour of the day.
- **Scatter Plot**: Shows the distribution of trips across different months.
- **Box Plot**: Illustrates trips by day of the week and month.
- **Pie Chart**: Displays the total trips by month.
- **Histogram**: Depicts weekly trips by month.

## Usage

To use the dashboard:
1. Clone or download this repository to your local machine.
2. Open the R Markdown file (`Uber_Data_Analysis_Dashboard.Rmd`) in RStudio.
3. Ensure you have the required packages installed (`flexdashboard`, `tidyverse`, `highcharter`, `gt`, `htmltools`, `viridis`).
4. Run the code chunks to generate the dashboard.
5. Explore the interactive dashboard to gain insights into Uber data.
