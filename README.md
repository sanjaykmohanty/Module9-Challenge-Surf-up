# Module9-Challenge-Surf-up

## Overview
The purpose of this project is to analyze temperature trends and provide recommendation on a particular location is suitable for opening a surf shop. Analysis of temperature data will help the shop owner determine if the surf and ice cream shop business is sustainable year-round.

The technical analysis covers the following:
- Summary Statistics for June temperature
- Summary Statistics for December temperature

## Resources
Software: Python 3.9.12, Jupyter Notebook 6.4.12
Data: hawaii.sqlite database

## Results
Using Python, Pandas functions and methods, and SQLAlchemy, a filter was created on date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June and December. Two DataFrames are created, one for the temperatures for the month of June and other one for the temperatures for the month of December. Summary statistics was generated for those DataFrames.

**Summary statistics for the June temperature**

![image](https://user-images.githubusercontent.com/31812730/197445098-7dd997a3-ce72-4d51-8f5e-5d11bc61d4d6.png)

**Summary statistics for the Decemeber temperature**

![image](https://user-images.githubusercontent.com/31812730/197445243-4555b7d1-fb02-408c-8539-2daf369d9c01.png)

## Summary
Although one can observe some variation in temperatures between June and Decemeber, the data suggests that the average temperature for both months is more than 70 degrees. As expected, June turns out to be slightly hotter month with the average temperature 3 to 4 degrees hotter than December. 

December minimum temperature is 56 degrees where as December average temperture is 71 degrees. There is a high chance that the temperture drops during the night in December where as during the day, the temperature remains at high sixties or at low seventies.

Maximum temperature is 85 degrees during June and 83 degrees during December. Temerature is reasonably high during both months which is a favorable condition for both water sports and ice cream.

Below are some ideas for further analysis for the client:

Analyze the differences in patterns for precipitation, so the client can understand the differences in rain between June and December to maximize his ability to draw tourism in.
Analyze the weather patterns at each indivudal weather station between june and december, to see if the location of his business, as well as the timing, will matter for drawing tourism. A similar analysis could be done for precipitation by station.
Analyze the temperatures in June and December throughout the day, this way they can see what the temperatures are like between the two season at certain times to help decide when to have the businesses open to attract the most tourists.
