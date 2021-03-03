# surfs_up

## Overview

In this module, we used Python, SQLAlchemy and Flask to analyze and visualize climate data as we prepared to open a surf shop. For this challenge, we gathered all our weather data from the months of June and December to compare the weather during these two months. The weather data we queried was stored in a SQLite database. 

## Results

Through our analysis, we were able to compare the weather results from the month of June through the month of December. The summaries of the results are shown below: 

June Statistics: 

![June Statistics](/resources/june_df_summary.png)

December Statistics:

![December Statistics](/resources/december_df_summary.png)

Key Differences:
- The average temperature for June was almost four degrees higher than the average for December. 
- December had a higher standard deviation, which means that temperatures were, on average, farther away from the mean temperature in December than in June. 
- Although the June maximum temperature was only two degrees higher than the max temp in December, the minimum temperature in December was 8 degrees lower than the minimum temperature in June. 

## Summary
Overall, although there is a difference between the temperatures in June and December, the difference is much less pronounced in Oahu than in many other parts of the world. It is reasonable to think that that the surf shop could operate year-round given the relative stability of temperatures. 

Below are som additional queries that may be helpful in our analysis: 
- compare the amount of rainfall on average for each month over the years
- get the temperature data for the months with the most rainfall

