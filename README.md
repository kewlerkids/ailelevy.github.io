# Analyzing the impacts of Power Outages caused by Natural Disasters across different regions in the US
## Project Overview
This is a data science project on if power outages are more likely to effect costal states more than inward states.

**Authors**: [Aile Banuelos](https://github.com/kewlerkids), [Levy Sahoo](https://github.com/levsah)

---

## Introduction

Welcome to our exploration of how severe weather affects power outages in the United States. Our analysis dives into a comprehensive dataset to uncover patterns between whether the location of a state matters in comparison to the amount of power outages they get. For example do coastal states tend to experience more power outages then states that are inland.

## Project Overview:
This project investigates [Why do some states that have power outages caused by Severe Weather have more power outages than others?], utilizing data from [Outage]. The dataset consists of [1534] records and includes key columns such as:

|Column	                 |Description|
|---                     |---        |
|`'Year'	`            |The year the outage occured|
|`'Month'`	                 |The month of the year the outage occurred |
|`'U.S._State'`	         |The state our outage occurred in|
|`'Climate.Region'`	     |The region of the US that this state is in|
|`'Anomaly.level'`	            |How much of an anomaly this power outage was |
|`'Outage.Duration'`	              |How long the outage lasted|

## ADD MORE HERE IF YOU THINK WE NEED MORE

Why This Matters: If you want to get a new home somewhere but want to have reliable power this could be useful. Company wise if companies wanted to put their focus more towards those areas that get outages more often to help they could also check and be able to help.


## Data Cleaning and Exploratory Data Analysis

### Cleaning Process

Our journey begins with cleaning the dataset to ensure the accuracy in our findings. We merged datasets, handled missing values, and removed outliers. This preparation was crucial for the integrity of our analysis.

### Exploratory Analysis

#### Univariate Analysis

#### Bivariate Analysis

## Hypothesis Testing

## Predicting Power Outages

### Framing the Prediction Problem

### Baseline Model

### Final Model Improvements

## Fairness Analysis

## Conclusion

Our analysis offers insightful findings on the impact of severe weather on power outages.

Notes for myself
Introduction
Begin with an overview of the project's focus on analyzing power outages and their relationship to severe weather events. Highlight the importance of this analysis in the context of infrastructure resilience and emergency response planning.
Step 1: Introduction and Question Identification
Present the project's primary question: How do severe weather events impact the frequency and severity of power outages?
Discuss the relevance of this question to the general public and stakeholders in emergency management and infrastructure maintenance.
Step 2: Data Cleaning and Exploratory Data Analysis
Detail the data cleaning process, including merging datasets, handling missing values, and ensuring data integrity.
Display a histogram of the distribution of outages over time and discuss any observed trends.
Embed a box plot illustrating the relationship between outage duration and weather severity.
Step 3: Assessment of Missingness
Discuss any columns in the dataset suspected of being NMAR and explain the reasoning.
Conduct permutation tests to examine the dependency of missing data on other columns, focusing on the ratings and outage duration.
Include visualizations related to missingness analysis and interpret the results.
Step 4: Hypothesis Testing
State the null and alternative hypotheses regarding the impact of severe weather on power outages.
Describe the permutation test conducted, including the choice of test statistic and significance level.
Present the p-value and conclude whether the data supports an increase in power outages due to severe weather events.
Steps 5-8: Predictive Modeling and Fairness Analysis
Step 5: Frame a prediction problem focusing on forecasting power outages based on weather conditions and other relevant factors.
Step 6: Describe the baseline model, including features used and model performance.
Step 7: Discuss improvements made in the final model and the rationale behind feature selection and hyperparameter tuning.
Step 8: Conduct a fairness analysis comparing model performance across different demographic groups or regions.
Summarize the predictive modeling and fairness analysis findings, highlighting any significant insights or implications for policy and planning.
Conclusion
Conclude with a summary of key findings and their implications for understanding and mitigating the impact of severe weather on power outages.
Suggest directions for future research or action based on the project's outcomes.
