# CMS Hospital Rating Analysis

Udacity Data Science Nanodegree - Project 1

## Motivation

Hospital quality ratings help patients make informed healthcare decisions. In this project, I explore hospital performance data from the Centers for Medicare & Medicaid Services (CMS) to understand which factors influence hospital overall ratings.

The analysis focuses on answering the following questions:

1. Can hospital ratings be predicted from quality metrics?
2. Which hospital performance indicators influence ratings the most?
3. How well can a machine learning model classify hospital ratings?

---

## Dataset

The dataset comes from the CMS Provider Data catalog:

https://data.cms.gov/provider-data

It contains quality measures for over 5,000 hospitals in the United States, including metrics related to:

- Mortality
- Patient safety
- Readmission rates
- Patient experience
- Timely and effective care

---

## Libraries Used

The analysis was conducted using Python and the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---


## Analysis Summary

The analysis followed the CRISP-DM process:

1. **Data Understanding**

Explored hospital rating distribution and examined missing values.

2. **Data Preparation**

Converted selected quality metrics into numerical format for modeling.

3. **Exploratory Data Analysis**

- Correlation heatmap
- Rating distribution
- Feature relationships

4. **Modeling**

A **Random Forest classifier** was used to predict hospital ratings.

5. **Evaluation**

Model performance:

- Accuracy: **~39%**
- Baseline accuracy: **~33%**

The model performs best at identifying **average and high-performing hospitals**, while intermediate ratings are harder to distinguish.

---

## Key Findings

The most influential variables for predicting hospital ratings were:

- Count of Safety Measures Better
- Count of MORT Measures No Different
- Count of READM Measures Worse
- Count of READM Measures Better

These results suggest that **patient safety and readmission outcomes play a major role in hospital ratings**.

---

## Blog Post

You can read the full analysis here:

[What Factors Influence Hospital Ratings? A Data Science Exploration](https://dev.to/arnaldovv/what-factors-influence-hospital-ratings-a-data-science-exploration-1ddj)
