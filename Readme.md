A Detailed Analysis on Factors Affecting the Healthcare Insurance costs
================
Nilutpaul Sarker Yash, Kate Passwater, Grace Schmitt, Sarah Bass

## Introduction

Healthcare insurance costs can vary widely between individuals, and
personal lifestyle and demographic factors often explain these
differences. Variables such as age, BMI, smoking status, number of
dependents, sex, and region may all play a role in shaping how much an
individual is charged for medical insurance.

The purpose of this project is to explore which factors are most
strongly associated with higher healthcare insurance charges. Using
exploratory data analysis in R, our team examined trends, distributions,
correlations, and interactions between variables in the dataset. Rather
than focusing on only one factor at a time, we also examined how
variables such as smoking status, BMI, and age interact to influence
insurance costs, since it is often a combination of factors that drives
insurance costs more than a single variable.

Overall, this project uses data visualization techniques and effective
statistical summaries to better understand the major patterns behind
healthcare insurance charges.

## Description of the Data

The dataset used for this project was obtained from Kaggle and contains
information about healthcare insurance costs and several personal
demographic and lifestyle-variables such as age, sex, bmi, number of
dependents and smoking status.

Dataset Source:
<https://www.kaggle.com/datasets/willianoliveiragibin/healthcare-insurance>

The dataset contains 1,338 observations and 7 variables, including both
numerical variables (age, BMI, number of children, and insurance
charges) and categorical variables (sex, smoking status, and region).

The variables included in the dataset are:

| Variable | Description |
|----|----|
| age | Age of the insured individual |
| sex | Gender (male or female) of the insured individual |
| bmi | Body Mass Index: A measure of body fat based on height and weight. |
| children | Number of dependents covered by insurance |
| smoker | Smoking status (yes or no) of the insured individual |
| region | Geographic region associated with the insurance record |
| charges | The medical insurance costs incurred by the insured person. |

Before beginning the analysis, the dataset was inspected for missing
values, variable types, and general structure. Several categorical
variables were converted into factors to improve the visualization and
exploratory analysis process. Additional grouped variables and summary
comparisons were also created throughout the project to better analyze
interactions between variables such as smoking status, BMI, and age.

## Research Questions

In order to understand how insurance charges can be affected by the
variables in the dataset, we decided to ask 8 main questions from the
data collected:

1)  Age and Charges - Is there a relationship between age and insurance
    charges?

2)  Sex and Charges – Do insurance charges differ by sex?

3)  BMI and Charges - Is there a relationship between BMI and insurance
    charges & is there a threshold where charges increase significantly?

4)  Smoker and Charges - Does smoking increase insurance charges?

5)  Children and Charges - Does insurance cost change with the number of
    dependents?

6)  Region and Charges - Are insurance charges greater in certain
    regions?

7)  Age and Smoking- Are older smokers charged more than those younger?

8)  Smoking and region- Do smokers in certain regions get charged more?

Our work throughout the project focuses on answering these main
questions by analyzing the dataset.

## Methods and Analytical Approach

The analysis was completed using R and RMarkdown. Several visualization
and exploratory analysis techniques were used throughout the project.

### The packages we used:

- tidyverse
- ggplot2
- corrplot

### The analytical techniques we used:

- Scatterplots
- Boxplots
- Violin plots
- Correlation matrices
- Faceted visualizations
- Distribution comparisons

### Ggraphing and visualizing techniques we used:

- Customized axis labels
- Cohesive color schemes (utilizing polishing plots techniques)
- Trend lines
- Grouped visualizations
- Faceted comparisons
- Simplified layouts for presentations

## Exploratory Data Analysis & Findings:
