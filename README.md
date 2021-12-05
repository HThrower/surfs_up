# surfs_up
Weather analysis using SQLite and SQLAlchemy. Climate App building using Flask. Other tools include Python and Jupyter Notebooks.

## Overview of the statistical analysis:
W. Avy likes your analysis, but he wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu to determine if the surf and ice cream shop business is sustainable year-round.

1. Explain the structures, interactions, and types of data of a provided dataset.
2. Differentiate between SQLite and PostgreSQL databases.
3. Use SQLAlchemy to connect to and query an SQLite database.
4. Use statistics like minimum, maximum, and average to analyze data.
5. Design a Flask application using data.

## Results:

### Total precipitation per day
![image](https://user-images.githubusercontent.com/31675832/144709577-8f884d9f-a644-46ee-bec3-c83600e01ead.png)

This data gives us a summary of different statistics for the amount of precipitation in a year. The count is the number of times precipitation was observed, which we see in 2021. The other statistics are the precipitation amounts for each station for each day. On average, we see precipitation being .177 and the max being 6.7 for the year.

## Temperture by month
![image](https://user-images.githubusercontent.com/31675832/144709606-de24bf99-7d30-4c97-a080-220ce3cc5da4.png)
![i+62mage](https://user-images.githubusercontent.com/31675832/144709617-215ac297-eacd-4b7c-9e64-3fe4d2d22cdd.png)

 We see that the count for June temperature is much higher than December, with a difference of 183 number of times precipitation was observed. However, the other statistics are very similar.

## Temperature observations

![image](https://user-images.githubusercontent.com/31675832/144708954-dfdfb7ca-a66f-4fb0-95f1-94718358e034.png)

The observations we see in Oahu were over 67 degrees. There are about 325 days where it was over 67 degrees when the temperature was observed.

## Precipitation on Oahu
![image](https://user-images.githubusercontent.com/31675832/144709178-59edc228-3851-4626-b4f4-a7487ad2abe6.png)

Here we see the temperature over a span of a few years, and based on the graph, we can determine that spring/summer has the highest precipitation on the island.

## Summary:
Overall, we see that for the month of June and December, we see an average temperature in the 70's allowing us an understanding that there is not much of a fluctuation in temperature. The island currently has low rainfall of 18% and consistent average weather. The area would be suitable for the business on the island.

Additional:
* Investing the sales of similar ice cream sales could be beneficial to understand how the weather affects the business
* Potential looking in further investigation of other months may be beneficial since it will be a year-round business

