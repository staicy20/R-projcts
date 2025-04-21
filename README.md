#Modelling malnutrition in Children Under Five in Kenya - Data Analysis Using R

This project explores the prevalence and contributing factors of malnutrition among children under five years old. Using R, the analysis investigates nutrition indicators, demographic variables, and socioeconomic factors to draw insights and support evidence-based decision-making.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Objectives](#objectives)
- [Tools and Packages](#tools-and-packages)
- [Analysis and Findings](#analysis-and-findings)
- [Results](#results)
  

## Project Overview

Malnutrition remains a leading public health concern among children under five, particularly in developing countries. This project uses statistical and machine learning techniques in R to analyze a dataset on child nutrition and identify key risk factors.

## Dataset

The dataset used includes the following variables:

- Child’s gender  
- Age of the mother  
- Marital status of the mother  
- Household wealth index  
- Region (Rural or Urban)  
- Level of education of the mother  
- Nutritional indicators: Stunting, Wasting, and Underweight 
The KDHS data was used.

## Objectives

- Explore and clean the dataset  
- Perform descriptive analysis including prevalence estimates  
- Conduct regression analysis to identify significant predictors  
- Calculate odds ratios and 95% confidence intervals  
- Build a logistic regression model to classify malnutrition  
- Evaluate the model using ROC curve and AUC  

## Tools and Packages

- R
- `tidyverse`
- `ggplot2`
- `dplyr`
- `readr`
- `caret` (for modeling)
- `pROC` (for ROC and AUC analysis)

## Analysis and Findings

The following were conducted:
Descriptive Analysis 
  - Prevalence tables showing proportion of stunting, wasting, and underweight children by demographic and socioeconomic characteristics

  Inferential Analysis
  - Logistic regression analysis  
  - Odds ratios with 95% Confidence Intervals to interpret the strength of associations  

  Machine Learning Model
  - Logistic Regression was used to predict malnutrition outcomes  
  - Performance evaluation using ROC Curve and AUC score  


