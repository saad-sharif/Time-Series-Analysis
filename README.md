# Time Series Analysis – National Energy Demand

## Project Overview

This project performs a **time series analysis of national energy demand** over a four-year period.  
Both **univariate** and **multivariate** techniques are applied to uncover:
- Cyclical and seasonal patterns in energy demand
- Relationships between demand and key external variables

The analysis focuses on understanding how **energy generation**, **temperature**, and **wind speed** relate to fluctuations in national demand over time.

---

## Objectives

- Explore temporal patterns and cyclicity in national energy demand
- Identify seasonal and recurring trends
- Analyze relationships between demand and:
  - Energy generation
  - Temperature
  - Wind speed
- Compare univariate and multivariate time series perspectives
- Provide insights relevant for energy planning and forecasting

---

## Data Source

### Primary Dataset
- `energy_demand.csv`
  - Contains national demand measurements over four years
  - Includes associated explanatory variables such as generation, temperature, and wind speed

---

## Technologies & Libraries Used

This project is implemented in **R** using the following packages:

### Data Manipulation
- dplyr
- lubridate

### Visualization
- ggplot2
- ggpubr
- gridExtra
- GGally
- corrplot

### Time Series Analysis
- tseries

---

## Environment Setup

Install the required packages using:

```r
install.packages(c(
  "ggplot2", "tseries", "gridExtra", "dplyr",
  "corrplot", "ggpubr", "GGally", "lubridate"
))
