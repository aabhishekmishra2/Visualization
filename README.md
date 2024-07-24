# Food Production in India

## Introduction

This repository contains an R project for visualizing data on crop production in India. The visualizations focus on various aspects such as year-wise, area-wise, and state-wise production. The project includes interactive elements implemented using Shiny dashboards.

## About Data

### Context

The dataset contains detailed information on crop production in India across various states over several years. It includes 7 columns and approximately 24,000 rows, with 624 unique values. The goal is to visualize crop production and productivity in India from multiple perspectives, including state-wise, season-wise, and year-wise analyses.

### Source

The data is sourced from [data.world](https://data.world/thatzprem/agriculture-india).

## Setup

### Prerequisites

Ensure you have the following R packages installed:

```r
install.packages(c("tidyverse", "dplyr", "tidyr", "ggplot2", "lubridate", "shiny"))
