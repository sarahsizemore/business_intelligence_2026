# Airbnb Market Analysis: Columbus vs New York

## Author
Sarah Sizemore

## Project Overview
This project analyzes Airbnb listing data to compare the Columbus, Ohio and New York City markets. The goal is to [briefly describe what decisions your analysis could support].

## Research Questions

1. Does the amount of listings per each host influence the price? 
2. What home types get the most reviews per month? 
3. Which hosts have multiple types of places? 
4. Which neighborhoods have the highest number of reviews? 
5. Do photos of the different rooms influence more interests and bookings?  

## Data Source Mapping

| # | Question | Data Needed | Source | Data Type |
|:-:|:---------|:------------|:-------|:----------|
| 1 | Does the amount of listings per each host influence the price?  |calculated host listing, price| listings.csv | Structured |
| 2 | What home types get the most reviews per month?  | room types, number of reviews per month | listings.csv, 	reviews.csv | Structured |
| 3 | Which hosts have multiple types of places?| Host ID, room types | listings.csv | Semi-structured |
| 4 | Which neighborhoods have the highest number of reviews? | Neighborhood, number of reviews, reviews per month | listings.csv., reviews.csv  | Structured |
| 5 | Do photos of the different rooms influence more interests and bookings?   | calendar, text descriptions, images | listings.csv, calendar.csv | Semi-structured|

## Data Overview
- **Columbus, Ohio:** 2878 listings (as of Sept 26, 2025)
- **New York City:** 36262 listings (as of Dec 4, 2025)
- **Primary data source:** [Inside Airbnb](http://insideairbnb.com/get-the-data)

## Project Status
- [x] Initial data exploration
- [x] Research questions defined
- [x] Data sources mapped
- [x] Data downloaded and cleaned
- [x] Analysis complete
- [x] Visualizations created
