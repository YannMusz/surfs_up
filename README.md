
## Purpose of project
1. Show the interactions, structures and the different types of data
2. Differences between SQLite and PostgreSQL
3. Make Flask application using the data provided

## Overview:
The purpose of our analysis is to understand temperature statistics for the months of June and December. We run our queries and store the temperatures in a list and consequently moving them into the data base. Once our dataframe up and running, we are able to get our summary statistics by using the .describe() method. Here are our results:
## Results:
### June Statistics for the Temperature and Precipitation

![Pic_1](https://github.com/YannMusz/surfs_up/blob/main/Resources/june_stat_temp_prcp.PNG)

### December Statistics for the Temperature and Precipitation

![Pic_2](https://github.com/YannMusz/surfs_up/blob/main/Resources/dec_stat_temp_prcp.PNG)

1. The mean temperature for June is of 75°F and is higher than the mean temperature of 71°F for December.  The oppositive is true for precipication. 

![Pic 3](https://github.com/YannMusz/surfs_up/blob/main/Resources/june_temp_graph.PNG)
![Pic 4](https://github.com/YannMusz/surfs_up/blob/main/Resources/dec_temp_graph.PNG)

2. Using the same range for the temperatures, June appears to have a slight left skew, where December is more uniform.    

![Pic 5](https://github.com/YannMusz/surfs_up/blob/main/Resources/june_temp_prcp_graph.PNG)
![Pic 6](https://github.com/YannMusz/surfs_up/blob/main/Resources/dec_temp_prcp_graph.PNG)

3. After Reviewing both scatterplots, the precipitation on average stays below 3 inches with a few outliers  of over 3 inches rain. 

## Summary:
The main concern was trying to find patterns to see if it is sustainable to run the Surf and Ice cream shop year-round.  Comparing the June and December weather patterns, the temperatures and precipitation means are reasonably similar. The conclusion is that the data strongly supports the claim of opening the shop year-round.
