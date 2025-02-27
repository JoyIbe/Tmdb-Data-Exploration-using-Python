# Tmdb-Data-Exploration-using-Python

## Introduction
This report presents an analysis of a dataset from TMDB. The dataset includes various details about movies, and the goal is to clean and analyze the data to derive insights.

## Data Import
- The dataset was imported using the `pandas` library.
- It was loaded from a CSV file named `tmdb_movies_data.csv`.
- Floating-point numbers were formatted to two decimal places for better readability.

## Data Cleaning
- Missing values were checked across all fields to identify gaps in the dataset.
- Datatypes were converted where necessary to ensure consistency and accuracy.

## Key Insights
- The distribution of movie ratings is approximately normal, with most ratings clustering between 5 and 7, peaking around 6, and fewer movies receiving extremely low or high ratings.
- The scatter plot shows that most movies have runtimes below 200 minutes with ratings clustered between 5 and 9, while longer movies are less frequent and exhibit a wider range of ratings.
- Drama|Horror|Mystery|Science Fiction|Thriller Category leads in the top movies in different genres by average rating.
- Avatar is leading as the movie with that generates the highest revenue, followed by Star Wars:The Force Awakens, Jurassic World.
- There is an increase over time with some fluctuations, especially after the 1980s, where revenue growth becomes more pronounced with higher peaks, mostly around 2000s.
- Jurassic World and Star Wars: The Force Awakens stand out with both high popularity and total revenue, while Mad Max: Fury Road has comparatively high popularity but lower revenue, and the remaining films show varied levels of popularity and earnings.

## Recommendation
- Avoid market saturation by choosing release dates with minimal competition from similar films and align releases with seasonal trends.

- Consider franchise-building as a strategy for sustained revenue growth.

- Leverage data-driven marketing to optimize promotional strategies for different audience segments.

- Explore international markets to maximize revenue potential.

## Conclusion
The analysis highlights the impact of production budgets, genre preferences, and industry trends on movie success.
Understanding these patterns helps stakeholders in the film industry make informed decisions on budgeting, marketing, and content creation.

