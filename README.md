# Zomato-Data-Analysis
Data analysis project on restaurant preferences and services using Pandas, Matplotlib, and Seaborn.

# Restaurant Data Analysis

This project involves analyzing restaurant data to answer key questions about restaurant services and preferences. The analysis focuses on understanding whether more restaurants offer online delivery compared to offline services, identifying the types of restaurants most favored by the public, and determining the preferred price range for couples dining at restaurants.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Libraries Used](#libraries-used)
- [Project Structure](#project-structure)
- [Steps in the Analysis](#steps-in-the-analysis)
  
## Introduction

The primary objective of this project is to analyze restaurant data from the Zomato dataset to draw insights about the restaurant industry. The analysis covers:

1. Whether more restaurants offer online delivery compared to offline services.
2. The types of restaurants most favored by the general public.
3. The price range preferred by couples for dining at restaurants.

## Dataset

The dataset used for this analysis is `Zomato data.csv`, which includes information such as restaurant names, types, votes, ratings, online order availability, and approximate costs for two people.

## Libraries Used

This project utilizes the following Python libraries:
- pandas: For data manipulation and analysis
- numpy: For numerical operations
- matplotlib: For data visualization
- seaborn: For statistical data visualization

  ## Project Structure

- `Zomato Data Analysis.ipynb`:The Code and Output of the project.
- `Zomato data.csv`: The dataset used for the analysis.

## Steps in the Analysis

1. **Importing Libraries:**
   - Import the necessary libraries such as pandas, numpy, matplotlib, and seaborn.

2. **Loading the Dataset:**
   - Load the dataset using pandas' `read_csv` function.

3. **Handling the Rating Data:**
   - Clean and convert the `rate` column to a numerical format.

4. **Checking for Null Values:**
   - Check for null values in the dataset to ensure data completeness.

5. **Exploratory Data Analysis (EDA):**
   - Visualize the data using various plots to explore columns like `listed_in(type)`, `online_order`, `rate`, and `approx_cost(for two people)`.

6. **Key Insights:**
   - Identify the restaurant with the maximum votes.
   - Analyze the distribution of ratings and costs.
   - Compare online and offline orders through visualizations like heatmaps.


