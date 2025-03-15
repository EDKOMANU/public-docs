# Dem - Demographic Analysis Package

Welcome to the documentation for Dem, a comprehensive R package designed for demographic analysis. This package provides tools for calculating various demographic metrics, population projections, and age structure analysis.

## Overview

Dem is an R package that offers a suite of functions for demographic analysis, including:

- Fertility metrics calculation (CBR, GFR, ASFR, TFR)
- Mortality analysis (CDR, ASDR, child mortality)
- Population projections
- Age structure analysis (Karup-King method)

## Key Features

### 1. Fertility Analysis
- Calculate Crude Birth Rate (CBR)
- General Fertility Rate (GFR)
- Age-Specific Fertility Rate (ASFR)
- Total Fertility Rate (TFR)

### 2. Mortality Analysis
- Crude Death Rate (CDR)
- Age-Specific Death Rate (ASDR)
- Child mortality metrics (neonatal, infant, child, under-5)

### 3. Population Projection
- Probabilistic population projections
- Multi-region support
- Bayesian-inspired simulation approach

### 4. Age Structure Analysis
- Karup-King method for age distribution
- Single-year age disaggregation from grouped data

## Getting Started

To get started with Dem, install the package from GitHub:

```r
# Install devtools if you haven't already
install.packages("devtools")

# Install Dem
devtools::install_github("EDKOMANU/Dem")
```

For detailed information about each feature, please navigate through the documentation sections.
