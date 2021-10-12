# Surfs Up Analysis

## Overview of Surfs Up Analysis

The purpose of the current analysis was to determine the feasibility of a new business venture, i.e., opening a surf and ice cream shop in Oahu. An analysis of weather data was conducted in order to obtain important information about whether or not weather trends through the course of a year would support this business venture, as it hinges on weather that is ideal for surfing and ice cream consumption. Analyses of interest included examining precipitation data, station data, monthly temperature data, and statistics and a Flask app was created so that the results could be shared via webpages with investors. Subsequently, it was requested that additional analyses be conducted to examine temperature data, specifically for the months of June and December, which ideally would illuminate whether or not this business venture could be sustainable all year long. 

## Resources
- Data Sources: hawii.sqlite (SQLite database)
- Software: VSCode, Jupyter Notebook, Python 

## Results

Summary statistics examining temperature observations were calculated for the month of June:  

![image](https://user-images.githubusercontent.com/85533099/136884458-42b59500-29e2-4e25-bf32-058d869f8aab.png)

Summary statistics examining temperature observations were calculated for the month of December:

![image](https://user-images.githubusercontent.com/85533099/136884558-f2634810-afef-4f0a-ae17-2b162994e800.png)

In comparing these results, we can see the following differences:

  -  The count of temperature observations is 1,700 in June versus 1,517 temperature observations in December
  -  The mean temperature observation for the month of June is 74.94 degrees with a standard deviation of 3.25 while the mean temperature observation for the month of December is 71.04 degrees with a standard deviation of 3.75. 
  -  The minimum temperature observation for the month of June is 64 degrees and 56 degrees for the month of December
  -  The temperature observation value falling at the 25th percentile is 73 degrees for June and 69 degrees for December

## Summary 

As described above, we see some differences in temperature observation counts, the mean temperature observation, the minimum temperature observation, and the temperature observation values falling at the 25th percentile. However, the other data points point to very similar observation values, including the median temperature observation at 75 degrees for June and 71 degrees for December as well as the temperature observation values falling at the 75th percentile (77 degress in June and 74 degrees in December). The maximum temperature observation values are almost identical with June at 85 degress and December at 83 degrees. Thus, the differences noted above do not necessarily reveal a substantial discrepancy in temperatures between the months of December and June, and summary statistics data show similar observed values. 

### Additional insights

Further analyses were conducted to help provide further clarification on weather trends during the months of June and December to understand whether the business venture of opening up a surf and ice cream shop could be successful all year long:

(1) A query was conducted to determine summary statistics of precipitation observations for the month of June:

![image](https://user-images.githubusercontent.com/85533099/136891268-df65e90f-0919-42de-b893-f9364b0e2d5f.png)

(2) A query was conducted to determine summary statistics of precipitation observations for the month of December:

![image](https://user-images.githubusercontent.com/85533099/136891347-6e466b8d-44a1-4f03-9df8-18af687fa42d.png)

  - According to the above query output, we again see a pattern of differences that are not necessarily so substantial to warrant concern that the surf and ice cream shop business venture would not be successful as a result of weather patterns. 


