# Surf’s Up: A Statistical Analysis of Climate Data for the island of Oahu
Utilizing SQLite, SQLAlchemy, Flask, Python and Jupyter Notebook.

## Overview of Statistical Analysis
The objective of this analysis is to review data on weather conditions for the island of Oahu, in Hawaii. The output will inform investors and decision-makers as to whether opening a surf shop and ice cream stand is a good business idea.

## Results
The original dataset contained weather data for the island of Oahu from August 23, 2016 - August 23, 2017. The requested analysis produced summary statistics for temperature readings on Oahu in the months of June and December. 

The results showed that:
*The average (mean) temperature in degrees Fahrenheit on Oahu was in the 70s in both December and June.
* The maximum temperature was in the mid-80s for both months, as well.
* The minimum temperature was 8 degrees lower in December, at a brisk 56 degrees F.
* The standard deviation – i.e., the average variance in temperature – is only slightly greater in December, by less than 0.5 degrees F.

![December_temps](https://user-images.githubusercontent.com/100387078/165133007-6e4f9c98-6990-4717-82b1-ea2c7e4c7ef6.png)![June_temps](https://user-images.githubusercontent.com/100387078/165133039-9849a9c8-a740-4bb1-9a41-82cf685fd870.png)

## Summary
The output of the analysis suggests there is consistently warm weather on Oahu throughout the year, without significant fluctuations or drops in temperature in the winter (December) compared to summer (June). 

However, while warm temperature makes both eating ice cream and surfing more enjoyable for people, it doesn’t tell the whole story. In order to assume that business will be consistent regardless of season, it would be prudent to perform further analysis on climate trends between June and December:
* Water temperature, wind speed, and wave/tide reports. Warm weather may entice people to eat ice cream, but there are other factors that will significantly affect surfing conditions. As currents change, there may be months that are much more attractive for people looking to surf. Temperatures may be consistent, but there may be no waves worth surfing every day. The surfing side of the business would do well to stay up-to-date on the best (and lesser-so) days for surfing.
* Cloud cover and precipitation. While you may be able to assume that precipitation will dampen customers for shops, cloud days (without rain) don’t attract people to the beach either. 
* Other months. Expanding the analysis to query climate data for other months may help confirm that weather is consistent year-round on Oahu, so that the 
business can better predict revenue and costs.

