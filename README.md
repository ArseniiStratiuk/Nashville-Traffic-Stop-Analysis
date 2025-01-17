# Nashville Traffic Stop Analysis

## Introduction

The goal of this project is to investigate whether the outcomes of traffic stops (such as warnings, citations, or arrests) differ significantly based on the type of violation and demographic characteristics of the individuals involved.

## Data Source

The data used in this project is sourced from the [Stanford Open Policing Project](https://openpolicing.stanford.edu/data/#:~:text=TN-,Nashville,-R). The dataset includes detailed information on traffic stops conducted in Nashville.

## Installation

To run the analysis, you need to have Python installed along with the following libraries:

- pandas
- seaborn
- matplotlib
- scipy

You can install the required libraries using pip:

```bash
pip install pandas seaborn matplotlib scipy
```

## Analysis

The analysis is divided into several steps:

### 1. Import Libraries and Load Data

The necessary libraries are imported, and the dataset is loaded using `pandas`.

### 2. Data Cleaning

The data is cleaned by removing missing values and duplicates to ensure the integrity of the analysis.

### 3. Data Exploration

Initial exploration of the data is performed to understand its structure and unique values in key columns.

### 4. Data Transformation

Data types are optimized, and necessary transformations are applied to prepare the data for analysis.

### 5. Visualization

Various visualizations are created using `seaborn` and `matplotlib` to explore the distribution of violations and outcomes, and to analyze the results based on demographic factors.

### 6. Statistical Analysis

Chi-square tests are conducted to determine if there are statistically significant differences in outcomes based on the type of violation, race, and gender.

## Conclusions

The analysis reveals the following key findings:

- The distribution of outcomes varies significantly based on the type of violation.
- There are notable differences in outcomes based on race and gender.
- Age also plays a role in the outcomes of traffic stops, with different age groups experiencing different results.
