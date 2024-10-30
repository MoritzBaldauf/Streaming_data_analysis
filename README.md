# Customer Base Analysis for Marketing Strategy

## Project Overview

This repository contains a comprehensive analysis of a streaming service's customer base, aimed at identifying potential premium subscribers and developing targeted marketing strategies. The project was completed as part of the Applications of Data Science course (1340).

## Key Objectives

-   Analyze customer behavior patterns and preferences
-   Identify promising customer segments for premium subscription conversion
-   Develop predictive models for premium subscription likelihood
-   Create data-driven marketing strategy recommendations

## Methods Used

-   **Clustering Analysis**
    -   K-means clustering
    -   DBSCAN clustering
-   **Predictive Modeling**
    -   Naive Bayes Classifier
    -   Classification Trees
    -   Random Forest
-   **Statistical Analysis**
    -   Correlation Analysis
    -   Exploratory Data Analysis
    -   Cross-validation

## Key Findings

-   Identified distinct customer segments based on income and subscription duration
-   Found that device type (Android/iOS) and living area (urban/rural) influence premium subscription patterns
-   Developed a Random Forest model that outperformed other classifiers in predicting premium subscription likelihood
-   Target cluster shows promising conversion potential based on predictive modeling

## Tools & Technologies

-   R Programming Language
-   Libraries:
    -   ggplot2 for visualization
    -   rpart for decision trees
    -   ranger for random forests
    -   dbscan for clustering
    -   dplyr for data manipulation
    -   And various other R packages for analysis and visualization

## File Structure

-   `Report.qmd`: Main analysis document with code and findings
-   `Group1_streaming_ds.rda`: Dataset used for analysis
-   `Summary_statistic_clusters.csv`: Generated cluster statistics

## How to Use

1.  Clone this repository
2.  Ensure R and required packages are installed
3.  Load the dataset using `load("Group1_streaming_ds.rda")`
4.  Execute the analysis in `Report.qmd`

## Contributors

-   Baldauf Moritz
-   Heinze Valentina
-   Kiseleva Nataliia

## Acknowledgments

This project was completed as part of the Applications of Data Science course (1340).
