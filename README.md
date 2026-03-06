# Tech Industry Layoffs Analysis

## Project Overview
This project analyzes global technology industry layoffs using SQL. The analysis includes data cleaning, transformation, and exploratory data analysis to identify trends across companies, industries, and countries.

## Tools Used
- SQL
- MySQL
- Data Cleaning
- Exploratory Data Analysis

## Dataset
The dataset contains information about global layoffs including:

- company
- location
- industry
- total_laid_off
- percentage_laid_off
- date
- stage
- country
- funds_raised_millions

## Data Cleaning Steps

The following data cleaning steps were performed:

- Removed duplicate records using ROW_NUMBER()
- Created staging tables for safe transformation
- Trimmed text values to standardize company names
- Converted date values using STR_TO_DATE()
- Handled missing values
- Standardized country names

## Exploratory Data Analysis

Key analysis performed:

- Total layoffs by company
- Layoffs by country
- Layoffs by year
- Layoffs by industry
- Rolling layoffs trends using window functions

## Key Insights

- 2023 recorded the highest layoffs
- United States had the largest layoffs
- Tech and crypto sectors experienced major layoffs
