# Data Science Internship Task 2: Data Cleaning and Exploratory Data Analysis(EDA) on Titanic Dataset

## Overview

This repository contains a comprehensive analysis of the Titanic dataset, focusing on data cleaning and exploratory data analysis (EDA). The goal of this project is to explore relationships between various features in the dataset and to identify patterns and trends regarding passenger survival rates.

## Dataset

The dataset used for this analysis is the Titanic dataset, which is publicly available on [Kaggle](https://www.kaggle.com/c/titanic/data). It contains data about the passengers on board the Titanic, including demographic and travel information, as well as whether each passenger survived the tragedy.

## Task Description

The primary objectives of this task are:

1. **Data Cleaning**: 
   - Identify and handle missing values.
   - Convert categorical variables into numerical formats for analysis.

2. **Exploratory Data Analysis (EDA)**:
   - Analyze the distribution of passenger ages.
   - Examine survival rates based on gender and passenger class.
   - Visualize key findings using histograms and bar plots.

## Steps Implemented

The analysis is performed using the following steps:

1. **Loading the Dataset**:
   - The dataset is loaded into a Pandas DataFrame.

2. **Understanding the Data**:
   - Basic statistics and information about the dataset are displayed.

3. **Checking for Missing Values**:
   - The presence of missing values is assessed, and strategies for handling them are proposed.

4. **Handling Missing Values**:
   - Missing `Age` values are filled with the median age.
   - Rows with missing `Embarked` values are dropped.

5. **Converting Categorical Variables**:
   - The `Sex` and `Embarked` columns are converted into numerical codes.

6. **Data Visualization**:
   - A histogram is plotted to visualize the distribution of ages.
   - Count plots and bar plots are generated to analyze survival rates by gender and passenger class.

## Results

- **Age Distribution**: The histogram shows the distribution of ages among passengers, revealing the majority age group.
- **Survival Rates**: 
  - The count plot indicates the overall survival rate.
  - The bar plots demonstrate that women had a higher survival rate than men and that first-class passengers had the highest survival rates.

## Libraries Used

- Pandas
- Matplotlib
- Seaborn
