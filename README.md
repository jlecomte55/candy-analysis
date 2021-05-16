# Candy Analysis

This repository contains notebooks for analyzing candy data from 
* [The Ultimate Halloween Candy Power Ranking](https://github.com/fivethirtyeight/data/blob/master/candy-power-ranking/candy-data.csv).
* [Most Popular Halloween Candy by State](https://www.candystore.com/blog/facts-trivia/halloween-candy-map-popular/).
* [Census Regions](https://github.com/cphalpert/census-regions/blob/master/us%20census%20bureau%20regions%20and%20divisions.csv).

The goal of this analysis was to determine what features impact Candy Demands.  At first, I analyzed the impact of features against solely Win Percent, or the given popularity. After this analysis, I experiemented with enriching the base dataset with Candy Sales and Geographic information for deeper insights, primarily to try predicting total pounds sold, as I believe this is a more powerful indicator of popular candy. 

-------------------
# High Level Approach
-------------------
High Level Approach:
1. Explored customer sentiment data to understand preferences
    * Analyzed Win Percent on Candy Features to understand key features driving positive sentiment
2. Sourced Candy Sales for 2020 to understand top selling candy
    * Compared drivers for top sales against customer sentiment data 
3. Gathered Geographical Data to understand regional preferences
    * Investigated regional drivers for candy with emphasis on North-East 
4. Prepared all three datasets to generate initial predictive models to forecast candy sales and understand significant features

-------------------
# Additional Data Information
-------------------
The Ultimate Halloween Candy Power Ranking data contains the following fields:

Header | Description
-------|------------
chocolate | Does it contain chocolate?
fruity | Is it fruit flavored?
caramel | Is there caramel in the candy?
peanutalmondy | Does it contain peanuts, peanut butter or almonds?
nougat | Does it contain nougat?
crispedricewafer | Does it contain crisped rice, wafers, or a cookie component?
hard | Is it a hard candy?
bar | Is it a candy bar?
pluribus | Is it one of many candies in a bag or box?
sugarpercent | The percentile of sugar it falls under within the data set.
pricepercent | The unit price percentile compared to the rest of the set.
winpercent | The overall win percentage according to 269,000 matchups.



