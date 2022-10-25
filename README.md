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
First, Python, Pandas functions and methods, and SQLAlchemy used, and a filter created on date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June and December. 
Next, two DataFrames created, one for the temperatures for the month of June and other one for the temperatures for the month of December. 
Finally, Summary statistics generated for those DataFrames.

**Summary statistics for the June temperature**

![image](https://user-images.githubusercontent.com/31812730/197445098-7dd997a3-ce72-4d51-8f5e-5d11bc61d4d6.png)

**Summary statistics for the December temperature**

![image](https://user-images.githubusercontent.com/31812730/197445243-4555b7d1-fb02-408c-8539-2daf369d9c01.png)

## Summary

**Key differences**
Although one can observe variation in temperatures between June and December, the data suggests that the average temperature for both months is more than 70 degrees. June is slightly hotter month with an average temperature close to 4 degrees hotter than the average temperature in December. 

December minimum temperature is 56 degrees whereas December average temperature is 71 degrees. There is a high probability that the temperature drops during the colder part of the day which could be during the night in December whereas during the rest of the day, the temperature remains at high sixties or at low seventies.

Maximum temperature is 85 degrees during June and 83 degrees during December. Temperature is high during both months which is probably a favorable condition for both water sports and ice cream.

The quartile measurements for both June and December are consistent, June is 3 to 4 degrees hotter than December.

**Additional queries** 
Temperatures may not be the only criteria to consider for this analysis. For instance, people may not go out surfing during heavy rain. Analysis of precipitation patterns during June and December could be another parameter to consider.

More analysis is needed to confirm the assumption that in December, the temperature is high during the day and the temperature drops during the night.

