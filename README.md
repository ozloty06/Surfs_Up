# Surfs_Up


## Project Overview
To lure an investor to invest in our Hawaiian Surf + Ice Cream Shoppe idea, this report analyzes weather, specifically temperature trends from 2010-2017 on the island of O'ahu, Hawai'i, in order to help assess the viability of building a year-round sustainable business. 

## Resources
- SQL Alchemy Queries on SQLite database
- Pandas and Numpy in Jupyter Notebook
- Python v.3.8.3

## Data Summary
For this analysis, June and December temperatures from pulled a data set that collected weather data from 2010-2017 on the Hawaiian island of O'ahu. This data was sorted into a dataframe using Pandas in a Jupyter Notebook in order to run summary statistics on the dataframe. The following insights were identified:
- Perhaps not surprisingly, mean temperatures in June were warmer than in December by almost 4° (3.90°).
- While maximum temperatures are comparable in June and December at 85° and 83° respectively, there's greater variance with minimum temperatures dropping to only 56° in December as compared to a warmer 64° in June.
- Further, the 25% percentile shows a larger variance in temperatures between June and December as compared to the upper percentiles.

![Image of June and December Summary Statistics](https://github.com/ozloty06/Surfs_Up/blob/main/Oahu%20Hawaii%20Temperature%20Analysis.png)
##### Fig. 1 - O'ahu, Hawai'i Summary Statistics for June and December temperatures for 2010-2017.

Interesting, the standard diviation of temperatures in Hawai'i is relatively low as compared with a state like Oklahoma. This means that while there's more variance in temperatures in December on the island of O'ahu as compared to June, the variation is still much less than you might see in Oklahoma that may have a similar mean temperature but likely has a much greater variety of temperatures when you compare June and December weather!

## Additional Analysis Recommendations

Based on our analysis, it appears the weather is quite stable year-round in Hawai'i, although there's slightly more variance and cooler temps in December.

To further understand the weather of this tropical paradise, it may be beneficial to also assess precipitation, humidity, and days of sunshine. These queries may require additional sources as our sample database does not include these additional weather parameters.
