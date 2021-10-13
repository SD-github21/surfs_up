# Surfs Up Analysis

## Overview of Surfs Up Analysis

The purpose of the current analysis was to determine the feasibility of a new business venture, i.e., opening a surf and ice cream shop in Oahu. An analysis of weather data was conducted in order to obtain important information about whether or not weather trends through the course of a year would support this business venture, as it hinges on weather that is ideal for surfing and ice cream consumption. Analyses of interest included examining precipitation data, station data, monthly temperature data, and statistics and a Flask app was created so that the results could be shared via webpages with investors. Subsequently, it was requested that additional analyses be conducted to examine temperature data, specifically for the months of June and December, which ideally would illuminate whether or not this business venture could be sustainable all year long. 

## Resources
- Data Sources: hawaii.sqlite (SQLite database)
- Software: VSCode, Python 3.7.10, Anaconda 1.7.2, Jupyter Notebook, Python, SQLAlchemy, Matplotlib, Numpy, Pandas, Flask 

## Results

Summary statistics examining temperature observations were calculated for the month of June:  

![image](https://user-images.githubusercontent.com/85533099/137063580-e84753cd-2cad-4d22-b715-9ea63f1cb545.png)

Summary statistics examining temperature observations were calculated for the month of December:

![image](https://user-images.githubusercontent.com/85533099/137063592-0eb5549a-7c31-4317-b1c2-583638fde503.png)

In comparing these results, we can see the following differences:

  -  The count of temperature observations is 1,700 in June versus 1,517 temperature observations in December
  -  The mean temperature observation for the month of June is 74.94 degrees with a standard deviation of 3.26 while the mean temperature observation for the month of December is 71.04 degrees with a standard deviation of 3.75. 
  -  The minimum temperature observation for the month of June is 64 degrees and 56 degrees for the month of December
  -  The temperature observation value falling at the 25th percentile is 73 degrees for June and 69 degrees for December

## Summary 

As described above, we see some differences in temperature observation counts, the mean temperature observation, the minimum temperature observation, and the temperature observation values falling at the 25th percentile. However, the other data points point to very similar observation values, including the median temperature observation at 75 degrees for June and 71 degrees for December as well as the temperature observation values falling at the 75th percentile (77 degrees in June and 74 degrees in December). The maximum temperature observation values are almost identical with June at 85 degress and December at 83 degrees. Thus, the differences noted above do not necessarily reveal a substantial discrepancy in temperatures between the months of December and June, and summary statistics data show similar observed values. Furthermore, the temperatures are generally hovering around the 70's, which is excellent weather for surfing.  

## Additional insights

Further analyses were conducted to help provide further clarification on weather trends during the months of June and December to understand whether the business venture of opening up a surf and ice cream shop could be successful all year long:

(1) A query was conducted to determine summary statistics of precipitation observations for the month of June:

![image](https://user-images.githubusercontent.com/85533099/137063737-7e33e58c-4f41-4bd6-aa8a-9bf2daa52027.png)

(2) A query was conducted to determine summary statistics of precipitation observations for the month of December:

![image](https://user-images.githubusercontent.com/85533099/137063748-45682a53-53d2-4939-8c78-54fdd32262d8.png)

According to the above query output:
  - The count for June precipitation observations is 1,574 versus 1,405 for December precipitation observations
  - The mean for June precipitation observations is 0.14 with a standard deviation of 0.34 while the mean for December precipitation observations is 0.22 with a standard deviation of 0.54
  - The maximum precipitation observed for June is 4.43 while the maximum precipitation observed for December is 6.42.  


For our additional analyses, we see a similar pattern of differences for precipitation observations as the temperature observations when comparing December and June. There are some key differences but there are also similarities. For example, the minimum precipitation observation as well as the precipitation observation value for the 25th percentile are 0.00 for both June and December. The median precipitation observation for June is 0.02 and 0.03 for December while the precipitation observation value for the 75th percentile are 0.12 for June and 0.15 for December. Furthermore, we see that the analysis trends yield precipitation observation data for both June and December that are quite similar to our summary statistics examining precipitation values for the year of August 2016 - August 2017. Therefore, it seems that these results provide even more evidence that the weather trends support the opening of a surf and ice shop in Oahu.

## Conclusions

**Therefore, based upon these findings, the differences in temperature and precipitation data between June and December are not substantial enough to warrant concern that the surf and ice cream shop business venture would not be successful as a result of observed weather patterns. In other words, it appears that this business venture of opening up a surf and ice cream shop could be very successful all year long based on observed weather patterns revealing suitable weather for both surfing and consuming ice cream.** 

