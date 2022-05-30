# surfs_up Read Me

## Overview

In preperation to open a surf supply and ice cream shop in Hawaii, an investor has asked for an analysis of weather patterns around potential shop locations. In this analysis we are looking at June and December on Oahu to determine the sustainability of a year-round shop.

## Analyis

In comparing the differences in temperature between June and December we have a few takeaways:

1. We have less data for December. For some reason there are almost 200 fewer recordings for December. While this may not impact our data much, it is an important observation

2. December is colder! Even though the average is only 3 degress less then June, the minimum temperature is 12 degress less. Do people still surf when it's 64 degrees in Hawaii? I don't know. But I've seen people surfing in the 40s in Minnesota!

3. The standard deviation is higher in December. So overall there are more swings. 

![June Stats](https://github.com/Olibabba/surfs_up/blob/main/resources/june_summary_stats.png)

![December Stats](https://github.com/Olibabba/surfs_up/blob/main/resources/dec_summary_stats.png)

In order to get some good practice I made sure to do the analysis using SQL queries as well as pythonic queries.

![Pythonic Query](https://github.com/Olibabba/surfs_up/blob/main/resources/Pythonic_query_dec.png)

![SQL Query](https://github.com/Olibabba/surfs_up/blob/main/resources/SQL_query_dec.png)

## Summary

In summary, the differences in temperatures between June and December are not large. Both months get into the 80s and average in the mid 70s. In my opinion this analysis shows that Oahu is a surfer's paradise as well as a perfect place to open a year round surf supply and ice cream shop. Surfs up!


To dig even deeper we could use a couple other queries. I only found these for December right now. If we wanted to explore further I would run these for June and compare.

Here I've found the average temperature and rainfall split by each station. This could impact the location we choose.
![Stats by Station](https://github.com/Olibabba/surfs_up/blob/main/resources/stats_by_station.png)


I've also gotten a finer detail of the temperature and rainfall by grouping each month's data by day.
![Stats by Day](https://github.com/Olibabba/surfs_up/blob/main/resources/stats_by_day.png)

This has the benefit of being nicely visualized!

![Avg Daily Rain in December](https://github.com/Olibabba/surfs_up/blob/main/resources/avg_rain_dec.png)

![Avg Daily Temp in December](https://github.com/Olibabba/surfs_up/blob/main/resources/avg_temp_dec.png)