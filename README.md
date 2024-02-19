# R-games-data-frame

## Overview

This project involves cleaning and analyzing a dataset of video game reviews from different platforms and generations. The dataset includes information such as user and meta scores, release dates, and platforms.

## Cleaning the Data

The dataset underwent several cleaning steps to prepare it for analysis:

- Excluded reviews marked as "tbd" to maintain consistency in comparisons.
- Converted the `user_review` column to numeric format and multiplied by 10 for consistency with meta scores.
- Created a new column `total_score` representing the combined user and meta scores.
- Removed leading whitespace from the `platform` column.
- Extracted the release year from the `release_date` column.
- Categorized games into generations based on release years.

## Preparing Data for Graphing

- Calculated average user, meta, and total scores per generation and platform.
- Converted the dataset from wide to long format for graphing purposes.

## Graphing

### Average Combined Score by Generation

- Bar graph showing the average combined game score for each generation.
- Line graph depicting the trend of average combined scores over generations.

### Average Combined Score by Platform

- Bar graph displaying the average combined game score for each platform.

### Average Metacritic and User Score by Generation

- Grouped bar graph illustrating the average user and metacritic scores for each generation.

### Average Metacritic and User Score by Platform

- Scatter plot representing the average user and metacritic scores for each platform.

## Conclusion

This project demonstrates the process of cleaning and analyzing a dataset of video game reviews, providing insights into average scores across different generations and platforms.
