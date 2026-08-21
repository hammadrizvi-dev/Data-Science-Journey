# Student Performance Analysis

## Overview

This project analyzes a small student performance dataset using Python and Pandas.

The objective is to understand how study hours, attendance, previous marks, and other variables relate to final student performance.

## Current Analysis

The analysis currently covers:

- Dataset inspection
- Data quality checks
- Missing-value detection
- Duplicate detection
- Data type inspection
- Filtering
- Grouped analysis
- Aggregation
- Performance improvement calculation

## Dataset

The dataset contains student-level academic information including study hours, attendance, previous marks, and final marks.

## Tools

- Python
- Pandas
- JupyterLab

## Day 3 — Exploratory Data Analysis

The third stage of the project focused on exploratory data analysis and visualization.

### Analysis Performed

- Scatter plots
- Pearson correlation
- Histogram
- Histogram bin analysis
- Correlation matrix
- Comparative analysis of numerical variables

### Key Findings

The analysis showed positive relationships between:

- Study hours and final marks — r ≈ 0.48
- Previous marks and final marks — r ≈ 0.46
- Attendance and final marks — r ≈ 0.39

Study hours showed the highest correlation with final marks among the variables analyzed.

However, correlation does not imply causation, and the findings should not be generalized beyond the available dataset.


## Day 4 — Advanced EDA Visualization

The fourth stage of the project focused on understanding relationships, distributions, and potential outliers using Seaborn-based visualizations.

### Analysis Performed

- Correlation heatmap
- Box plot
- Interquartile Range (IQR)
- Potential outlier detection
- Pair plot for multi-variable exploration

### Correlation Heatmap

A correlation heatmap was used to visualize the correlation matrix and identify the strength and direction of relationships between numerical variables.

Key observations:

- Study hours and final marks showed a moderate positive correlation (r ≈ 0.48).
- Previous marks and final marks showed a moderate positive correlation (r ≈ 0.46).
- Attendance and final marks showed a weaker positive correlation (r ≈ 0.39).
- Study hours and previous marks showed a very weak negative correlation (r ≈ -0.11).

### Outlier Analysis

A box plot was used to examine the distribution of final marks and identify potential outliers.

The Interquartile Range (IQR) method was then used to verify potential outliers programmatically.

For `final_marks`:

- Q1 = 59.8
- Q3 = 68.5
- IQR = 8.7
- Lower Bound = 46.75
- Upper Bound = 81.55

No potential outliers were identified in `final_marks` using the IQR method.

### Pair Plot

A pair plot was introduced as a multi-variable exploratory visualization.

It provides a quick overview of pairwise relationships between numerical variables and the distribution of individual variables.

The pair plot was used for pattern discovery rather than drawing final conclusions from visualization alone.

### Key Learning

The main focus of Day 4 was understanding that different visualizations serve different analytical purposes:

- Heatmap → compare correlations across multiple variables
- Box plot → understand distribution and potential outliers
- Pair plot → quickly explore multiple variable relationships

Visualizations help identify patterns, but conclusions should be supported by appropriate analysis and statistical measures.

### Current Status

- Day 1: Data Analysis Fundamentals ✅
- Day 2: Data Cleaning & Grouped Analysis ✅
- Day 3: Exploratory Data Analysis & Correlation ✅
- Day 4: EDA Visualization & Outlier Analysis ✅