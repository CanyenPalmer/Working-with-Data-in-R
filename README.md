# Working with Data in R – Foundations for Analytical Workflows

This repository contains structured documentation and code examples for data wrangling and exploratory data analysis using R. The Quarto notebook focuses on practical, reproducible workflows built around the `tidyverse` and base R, emphasizing common operations used across analytics, business intelligence, and machine learning projects.

## Objective

To establish a core understanding of data loading, transformation, summarization, and visualization in R—skills critical for both prototyping and production-level analytical work.

## Tools and Packages

- **R**: Statistical computing environment
- **Quarto**: Literate programming framework for reproducible reports
- **Tidyverse**:
  - `readr` / `readxl`: Data import
  - `dplyr`: Data transformation
  - `ggplot2`: Visualization
  - `tibble`: Tidy data frame structure
- **Base R**: For foundational operations

## Topics Covered

### Data Import and Cleaning

- Loading CSV and Excel files using `read_csv()` and `read_excel()`
- Handling missing values with `is.na()` and filtering logic
- Column inspection and type correction using `str()` and `mutate()`

### Tidy Data Principles

- Emphasis on long vs. wide data formats
- Use of `pivot_longer()` and `pivot_wider()` for reshaping
- Tidying messy datasets for analysis or modeling readiness

### Data Transformation

- Selecting and renaming variables with `select()`, `rename()`
- Creating new features using `mutate()`, `case_when()`, and conditional logic
- Grouped summaries via `group_by()` + `summarise()`
- Row-wise filtering using `filter()`, logical conditions, and `between()`

### Exploratory Summarization

- Counting with `count()` and `n()`
- Generating descriptive statistics: mean, median, sd, IQR
- Using `arrange()` for ordered analysis and outlier identification

### Data Visualization

- Scatterplots, histograms, and bar plots with `ggplot2`
- Grouped and faceted charts using `facet_wrap()` and `aes()` mappings
- Introduction to layering and aesthetic control in `ggplot`

## Use Cases and Applications

These techniques map directly to real-world use cases in:

- Pre-modeling data preparation and QA
- KPI aggregation and business metric generation
- Ad hoc data investigations
- Analytical dataset construction for forecasting or classification

## Relevance for Data Science and Analytics Roles

This document reinforces fundamental programming and analysis techniques that are essential for:

- Data pipeline development
- Exploratory modeling and feature selection
- Cross-functional reporting and dashboard development
- Communicating data-driven insights to technical and non-technical audiences

## Getting Started

1. Open the `.qmd` file in RStudio.
2. Ensure the `tidyverse` package is installed:
   ```r
   install.packages("tidyverse")
