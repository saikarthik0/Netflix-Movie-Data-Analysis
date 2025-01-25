# Netflix Movies Data Analysis using Python

![](https://github.com/saikarthik0/Netflix-Movie-Data-Analysis/blob/main/logo.png)

## Overview
This project involves a comprehensive analysis of Netflix's movies data using Python. The goal is to extract valuable insights and answer various business questions based on the dataset. The following README provides a detailed account of the project's objectives, business problems, solutions, findings, and conclusions.

## Business Problems
**Business Problem:** [Presentation ppt](https://github.com/saikarthik0/Netflix-Movie-Data-Analysis/blob/main/movie%20data%20analysis%20project%20ppt.pptx)

- What is the most frequent genre of movies released on Netflix?
- What genres has highest votes?
- Which movie got the highest popularity? What's its genre?
- Which movie got the least popularity? What's its genre?
- Which year has the most filmmed movies?

## Dataset

The data for this project is sourced from the Kaggle dataset:

- **Dataset Link:** [Movies Dataset](https://github.com/saikarthik0/Netflix-Movie-Data-Analysis/blob/main/mymoviedb.csv)

## Exploratory Data Analysis (EDA)

- Our Dataframe consists of 9827 rows and 9 columns.
- Our Dataset looks a bit tidy with no NaNs nor duplicated values.
- Release_Date is in 'String Datatype' needs to be casted to date time to extract only the year.
- 'Overview','Original_language' and 'Poster_Url' wouldnt be so useful during analysis, so we will drop them.
- There are noticable outliers in Popularity column.
- 'Vote_Average' better be categorized for proper analysis.
- Genre column has comma separated values and white spaces that needs to be handled and casted into category.  

## Process
- Verified the dataset for any missing values and anomalies, and addressed them appropriately to ensure data completeness and integrity.
- Ensured the dataset is consistent and clean in terms of data types, formats, and values, adhering to the requirements of the analysis.
- Removed unused or irrelevant columns to reduce noise and focus on relevant features for the analysis.
- Converted data types to those suitable for analysis, ensuring alignment with the requirements of the business problem.
- Prepared the dataset to be fully processed and ready for analysis, ensuring it meets all quality standards for accurate and reliable insights.

- **Jupyter Notebook Guide for Project:** [Python Code](https://github.com/saikarthik0/Netflix-Movie-Data-Analysis/blob/main/Netflix%20Movie%20Data%20Analysis.ipynb)

## Visual Analysis of the Business Problem

<div style="display: flex; justify-content: space-around;">
  <img src="https://github.com/saikarthik0/Netflix-Movie-Data-Analysis/blob/main/Business%20Problem%201.png" alt="Analysis for Business Problem 1" width="300"/>
  <img src="https://github.com/saikarthik0/Netflix-Movie-Data-Analysis/blob/main/Business%20Problem%202.png" alt="Analysis for Business Problem 2" width="300"/>
  <img src="https://github.com/saikarthik0/Netflix-Movie-Data-Analysis/blob/main/Business%20problem%205.png" alt="Analysis for Business Problem 5" width="300"/>
</div>
  <img src="https://github.com/saikarthik0/Netflix-Movie-Data-Analysis/blob/main/Business%20Problem%203.png" alt="Analysis for Business Problem 3" />
  <img src="https://github.com/saikarthik0/Netflix-Movie-Data-Analysis/blob/main/Business%20Problem%204.png" alt="Analysis for Business Problem 4" />

## Answering the Business Problem

- 'Drama' genre is the most frequent genre in out dataset and has appeared more than 14% of the times among 19 other genres.
- We have 25.5% of our dataset vote (6520 rows). Drama again gets the highest popularity among fans by being having more than 18.5% of movies popularities.
- Spider-Man : No Way Home, has the highest popularity rate in our dataset and it has genres of Action, Adventure and Silence Fiction.
- The United States, Thread has the least rates in our dataset and it has genres of music, drama, war, sci-fi and history.
- Year 2020 has the highest filmming rate in our dataset.

