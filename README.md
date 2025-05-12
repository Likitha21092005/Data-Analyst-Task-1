# Data Cleaning and Preprocessing

## Overview
This project focuses on cleaning and preprocessing the Netflix Movies and TV Shows dataset, transforming raw data into an analysis-ready format using Excel. 

## Dataset
- Dataset Used: [Netflix Movies and TV Shows](https://www.kaggle.com/datasets/narayan63/netflix-popular-movies-dataset)
- Standardized Date Format: "2020" (year only)

## Key Cleaning Steps Performed
1. Date Standardization:
   - Extracted only the year from all date fields
   - Used Excel formula: `=YEAR(date_value)` or `=RIGHT(A2,4)` for text dates
   - Created new "year_added" column

2. Handled Missing Values:
   - Identified blanks using Excel filters
   - Marked missing categorical data as "Unknown"
   - Set missing numerical values to 0

3. Removed Duplicates:
   - Used Data → Remove Duplicates
   - Verified uniqueness based on show_id

4. Standardized Text Values:
   - Consistent capitalization (e.g., "Movie" not "movie")

