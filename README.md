# British Airways Reviews Data Dashboard
![Screenshot of a comment on a GitHub issue showing an image, added in the Markdown, of an Octocat smiling and raising a tentacle.](https://github.com/realpauly/British-Airways-Reviews-Dashboard-using-Tableau/blob/main/review-flight.jpg)

## Introduction
This project presents a data dashboard developed using Tableau to visualize customer reviews for British Airways. The dashboard analyzes various metrics such as overall ratings, cabin staff service, food, entertainment, and more, offering insights into customer experiences.

## Problem Statement
The goal is to analyze customer feedback to identify patterns and trends in British Airways services. This includes understanding how different traveler types, seat classes, and aircraft impact customer ratings.

## Skills Demonstrated
Data visualization
Data transformation and cleaning
Data modeling using relationships in Tableau
Dashboard creation for interactive analysis

## Data Sourcing
The dataset was sourced from Kaggle and consists of two CSV files: one containing customer reviews and another with country information.

## Data Transformation
Data cleaning and transformation were done using Tableau Prep. This involved handling missing data, filtering, and merging the datasets based on a many-to-many relationship between reviews and countries, with a key relationship set as "place = country."

## Modeling
The data model in Tableau established a many-to-many relationship between the reviews and countries dataset. This model helped aggregate data across various filters, such as traveler type, aircraft, and country.

## Analysis and Visualization
The Tableau dashboard includes multiple visualizations:
Time series chart displaying average overall ratings by month
Geographic map showing ratings by country
Aircraft-specific rating comparisons
Filters for traveler type, seat type, and more

![British Airways Review Dashboard](https://github.com/realpauly/British-Airways-Reviews-Dashboard-using-Tableau/blob/main/Tableau Project.png)


## Conclusion and Recommendation
This analysis reveals distinct patterns in customer satisfaction across different aircraft and traveler categories. British Airways could focus on improving areas like entertainment and food, based on lower average ratings. Further analysis could explore how specific services impact customer loyalty.
