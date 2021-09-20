# Pyber Analysis

## Overview of Analysis

This analysis compared the ridership and revenue collected by Pyber by different types of cities (urban, suburban, and rural). As part of the analysis, I created a multi-line plot that visualizes the total fare per week in each city type and also created a dataframe that summarized the total and average fares per ride and per driver in each city type.

## Results

![plot_image](https://github.com/teruki-i/Pyber_Analysis/blob/b631f9304d6620549d44d10510d336d6e8220bfa/analysis/Pyber_fare_summary.png)

As the multi-line plot shows, urban cities earned the most revenue. In the first week of January 2019, which was the worst performing week in these cities, urban cities collected approximately $1,700 in fares. Then in the last week of February and second week of March, which were the two best performing weeks, total fares were about $2,500.

Suburban and rural cities earned significantly less.

Even at the best performing weeks in the end of both Febraury and April, suburban cities earned approximately $1,400 in fares (approximately 82% of the worst performing week in rural cities). At the lowest point (the first week of January), suburban cities earned approximately $750.

Rural cities managed to only bring in $500 in their best performing week at the begining of April (just under 30% of the urban low point). And at the lowest point, which was in the second week of January, rural cities earned less than $100.

These disparities might be because of the lack of drivers and higher cost of rides in both rural and suburban cities.

![summary_df_image](https://github.com/teruki-i/Pyber_Analysis/blob/b631f9304d6620549d44d10510d336d6e8220bfa/analysis/pyber_summary_df.png)

With almost $40,000, urban cities collected multiple times the fares collected in both suburban and rural cities (approximately double the total suburban fare and nine times the total rural fare). It's immediately clear that this is because the total urban ride count of 1,625 was much more than the rideship in suburban and rural cities (more than double the total combined ride count of suburban and rural cities). Because of this, the fare per ride is higher in both suburban and rural cities. While the average fare per ride was $24.53 in urban cities, it was $30.97 in suburban cities and $34.62 in rural cities. Thus, users might be discouraged from using Pyber because of higher fares in the suburbs and countryside.

However, it's also important to key in on the total number of drivers. Urban cities had 2,405 drivers, while suburban cities only had 490 drivers and rural cities had 78 drivers. Thus the higher fare per ride in suburban and rural cities might simply be a supply and demand issue. Due to a lack of drivers, rides were more expensive.

Consequently, the average fare per driver was also higher in suburban and rural cities than in urban cities. While the average was $16.57 in urban cities, at $39.50, the average was approximately 2.5 times that in suburban cities. And at $55.49, the average was more than triple that in rural cities. Furthermore, urban cities in total had more drivers than there were rides (2,405 drivers for 1,625 rides)--this wasn't the case in either suburban and rural cities. Thus, these drastic differences in average fare per driver are largely because many drivers in urban cities failed to give any rides and earn any revenue at all because of competition with other drivers.

## Summary

In order to increase ridership and thus the revenue stream from rural and suburban cities, Pyber should consider one or more of the following.

### Lower the price of rides in suburban and rural regions

As mentioned above, potential riders might be turning away from Pyber in the suburbs and countryside because of the higher fares per ride. While these higher fares seem to be largely a supply and demand issue, it would be prudent to modify the fare calculation method to take into account the type of city that riders are in. If the calculations lower the fares in rural and suburban areas to be in line with those of urban areas, more riders may be pulled into using Pyber.

### Recruit more drivers in suburban and rural regions

The average fare per ride in suburban and rural regions could be lowered by also dealing with the supply side of the issue. Bringing in more drivers to these regions would naturally drive down the price of each ride. In order to recruit more drivers, the current high average fare per driver could be used in recruitment ads. However, as drivers increase and the average fare per driver decreases, the recruitment strategy will likely have to be adjusted in order to continue attracting more drivers.

### Provide relocation insentives for urban drivers

As the results point out, urban cities had too many drivers, including many who didn't manage to give any rides. If some of these drivers leave urban cities, they would be dealing with less competition from other drivers while also increasing the supply of drivers in suburban and rural regions. This could help with increasing the ridership in these regions. Furthermore, this wouldn't decrease the total fare collected in urban cities. As supply outstripped demand in urban cities, it's possible to cut the number of drivers without causing a decrease in ridership.

Marketing material advertising the higher fare per driver in suburban and rural areas might convince drivers to relocate, but again, this likely won't work as a long-term strategy as the average fare per driver decreases. Instead, drivers might be convinced to move if provided relocation bonuses. Though this could be a steep investment, in the long-term, this could resolve the supply side issue in suburban and rural regions, thereby increasing total ridership and total fares in these cities.

## Consideration for Further Analysis

While this analysis determined that the disparities between the different types of cities was mostly a supply issue, it might also help to consider mileage and trip duration. The results suggested that ridership was lower in suburban and rural cities due to higher prices caused by a lack of drivers. However, higher fares could also be because of longer distances driven for each ride. As the suburbs and countryside tend to be more spread out than urban areas, the average trip in suburban and rural cities might simply be longer than in urban cities. This analysis, however, lacked data on mileage and trip duration and can't provide insight on this point.  