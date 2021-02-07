# surfs_up

## Overview Of Analysis

After developing a passion for both surfing and ice cream in Oahu, Hawaii, a dream was inspired to open a surf and shake shop to locals and tourists within the area. In order to successfully run the shop, investor backing will be needed. W. Avy is a famous investor with a similar passion to surfing. He agreed to back the shop, but needs a full weather analysis on the city of Oahu in order to fully commit. W. Avy has requested temperature data for the months of June and December to determine if the surf and shake shop is sustainable all year round. The purpose of the analysis is to provide a summary statistic analysis to W. Avy so he can make a choice as to whether he would like to fund the shop. 

## Results

### June Weather Data

In order to obtain June weather data over a period of 7 years in Oahu, Python, SQLite, and SQLAlchemy were utilized to analyze the temperature patterns. The following temperature trends were found within the month of June. 

- Mean Temperature: 74.94 degrees
- Standard Deviation: 3.25
- Minimum Temperature: 64 degrees
- Maximum Temperature: 81 degrees

### December Weather Data

In order to obtain December temperature data over a period of 7 years, Python, SQLite, and SQLAlchemy were also utilized to analyze temperature trends. The following trends were found:

 - Mean Temperature: 71.91 degrees
 - Standard Deviation: 3.29
 - Minimum Temperature: 65 degrees
 - Maximum Temperature: 78 degrees
 
 ### Differences Between June and December Temperatures
 
There were three main differences in temperature patterns between the months of June and December. The first key difference was the mean temperature of each month. June had a higher temperature mean with 74.94 degrees compared to December which had a mean of 71.91 degrees. The second major difference was the maximum temperature. In June, the max temperature was 81 degrees whereas in December the maximum temperature was 78 degrees. The third observation was that the minimum temperature was only different by 1 degree. The minimum temperature in June was 64 degrees and the minimum temperature for December was 65 degrees. 

## Summary

The weather patterns in Oahu within the months of June and December were not drastically different from each other. Although June was slightly warmer on average than December, the two months were only 4 degrees apart. This is great news for the surf and shake shop, as the temperature is pretty consistent even in different months. The minimum temperature for each month does not seem to drop below 64 degrees and does not reach too high beyond 81 degrees which are great temperatures for both surfing and eating ice cream. Two additional queries I would perform to gather more data for the months of June and December would be to look at a wholistic weather trend analysis year round for Oahu. There may be some months that have different weather patterns that are worth looking for. Also, I would create a query to look at a line graph at each of the months to visualize the temperature pattern trends and identify which months are outliers and get a better understanding of the minimum and maximum temperatures for each month. 


