# Marketing-A-B-Testing-Analysis

This project analyzes an A/B testing dataset from a marketing campaign to determine the effectiveness of advertisements in driving conversions. The analysis involves hypothesis testing, effect size calculation, confidence intervals and visualizations.


## Introduction

Marketing companies often run A/B tests to evaluate the success of their campaigns. In this project, we analyze the results of an A/B test, where one group of users was shown ads (experimental group) and the other group was shown public service announcements (control group). Our goal is to determine if the ads significantly impacted conversion rates and to quantify the effect size.

## Dataset
The dataset used for this analysis is sourced from Kaggle and contains the following fields:

`user id`: Unique identifier for each user.

`test group`: Indicates if the user saw an ad or a PSA.

`converted`: Whether the user made a purchase (True/False).

`total ads`: The number of ads the user saw.

`most ads day`: The day of the week when the user saw the most ads.

`most ads hour`: The hour of the day when the user saw the most ads.


## Project Workflow

### Data Exploration & Preprocessing:

* Load the dataset, explore key statistics, check for missing data.
* Hypothesis Testing:
    Perform Z-tests for proportions to determine if the difference in conversion rates between the ad and PSA groups is statistically significant.
* Effect Size Calculation:
    Calculate Cohen's h to measure the practical impact of the ads.
* Confidence Intervals:
    Compute 95% confidence intervals for conversion rates and the difference between the two groups.
* Visualizations:
    Generate visual representations, including bar plots, histograms and confidence intervals.
    
## Key Findings

* The Ad Group had a conversion rate of ~2.55%, while the PSA Group had a conversion rate of ~1.79%.
* The Z-test showed a statistically significant difference between the groups (P-value < 0.05).
* The effect size, measured by Cohen's h, was small (~0.05), indicating that while the ads had an effect, the practical impact on conversion rates was modest.
* The 95% confidence interval for the difference in conversion rates was `0.00595, 0.00943`, confirming that the ads led to a small but significant increase in conversions.

## Visualizations

The following visualizations are included in the analysis:

* Conversion Rate Bar Plot: Compares the conversion rates of the Ad and PSA groups.
* Distribution of Ads Seen: Shows the distribution of total ads seen by users in both groups.
* Confidence Intervals: Visualizes the conversion rates and their 95% confidence intervals for both groups.