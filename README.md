# Extract Transform Load Project : Maybelline Foundation 


## Project Proposal

In this project, we will be combining 2 datasets that will show the following:

-Number of foundation shades available offered by top leading makeup company of 2018, Maybelline Cosmetics
-Number of products available within Maybelline Cosmetics
-Revenue growth (in millions) for Maybelline Cosmetics, in 2018

## Extract
Data was extracted from Kaggle [https://data.world/the-pudding/diversity-of-makeup-shades]. This data shows the foundation shade range availability for Maybelline Cosmetics in 2018. 
Data was also extracted from statistica [https://www.statista.com/statistics/194815/leading-us-foundation-brands-in-2013-based-on-sales/]. This data shows the leading foundation brands in the United States in 2018, based on sales in the million, in U.S. Dollars. 

## Transform
Data was transformed using pandas, specifically:
-Dataset from statistica was converted from xlsx file and converted to a csv file.
-Datasets were loaded into pandas as CSV files.
-Modification of dataset columns, removing useless columns(i.e, other makeup brands) and renaming columns.
-Data was parsed to group Maybelline Cosmetics foundations, by product, based on number of makeup shade availability (hex count per product).
-Data from statistica was joined to show leading foundation brands based on foundation sales.


## Load

-Final datasets were joined and loaded into Postgres, via primary key 'brand'.
# Maybelline-Foundation
