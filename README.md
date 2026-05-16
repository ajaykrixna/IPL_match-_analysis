# IPL Match Analysis

## About
Exploratory Data Analysis on IPL matches from 2008-2017

## Dataset
- matches.csv - 628 matches, 17 columns
- deliveries.csv - 150,460 deliveries, 21 columns

## Tools Used
Python, Pandas, NumPy, Matplotlib, Seaborn, Google Colab

## Data Cleaning
- Dropped umpire3 column (100% missing)
- Dropped rows with missing city values (7 rows, <1%)
- Filled missing winner with 'No Result' (abandoned matches)
- Filled missing player_of_match with 'No Result'
- Removed single row with missing umpire data

## Analysis Done
- GroupBy Analysis — top teams, players, cities
- Toss win percentage per team
- Pivot table — toss decision vs match wins
- Merged match and delivery data for player analysis
- Top 10 run scorers and wicket takers
- Season wise champions (2008-2017)
