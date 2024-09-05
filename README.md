# Statistical Analysis in Python

This repository contains a Python script for performing statistical analysis on a medical dataset. The dataset includes information on various factors such as the year, age, tumor size, and breast quadrant associated with a diagnosis result (Benign or Malignant). The analysis covers basic descriptive statistics, hypothesis testing, confidence intervals, and regression analysis.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Analysis](#analysis)
  - [Descriptive Statistics](#descriptive-statistics)
  - [Hypothesis Testing](#hypothesis-testing)
  - [Confidence Intervals](#confidence-intervals)
  - [Regression Analysis](#regression-analysis)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The goal of this project is to conduct a comprehensive statistical analysis on a medical dataset. The analysis includes calculating basic descriptive statistics, performing a one-sample t-test, computing confidence intervals, and building a linear regression model to understand the relationship between age and tumor size.

## Dataset

The dataset used for this analysis contains the following columns:
- **Year:** The year of diagnosis.
- **Age:** The age of the patient.
- **Tumor Size (cm):** The size of the tumor in centimeters.
- **Inv-Nodes:** Number of involved lymph nodes.
- **Breast:** Side of the breast affected (Left or Right).
- **Metastasis:** Presence of metastasis.
- **Breast Quadrant:** The quadrant of the breast where the tumor is located.
- **History:** History of breast cancer.
- **Diagnosis Result:** Outcome of the diagnosis (Benign or Malignant).

## Analysis

### Descriptive Statistics
The following basic descriptive statistics are calculated:
- Mean
- Median
- Mode
- Standard Deviation
- Variance
- Range
- Skewness
- Kurtosis

### Hypothesis Testing
A one-sample t-test is performed to compare the sample mean of the "Age" column against a hypothetical population mean. The t-statistic and p-value are reported.

### Confidence Intervals
The 95% confidence interval for the "Age" column is computed to understand the range within which the true population parameter lies.

### Regression Analysis
A linear regression model is built to study the relationship between the patient's age and tumor size. The results include the R-squared value, coefficients, and statistical significance of the model.

## Dependencies

The following Python libraries are required to run the analysis:
- `pandas`
- `numpy`
- `scipy`
- `statsmodels`

## Thank You

