# Surfs_up
Surfs_up
#CHALLENGE OVERVIEW (DJB)
this project explores the weather data in hawaii and introduces us to dependencies like sql lite and flask. We used "advanced data storage" from the hawaii.sqlite file to retreive temperature data. Can this surf shop function as a viable year round business? mostly likey, yes. 

##SOURCES
Hawaii.sqlite, climate_analysis.ipynb
Python sql toolkit, anaconda powershell, object relational mapper, pandas, matplotlib, numpy, and flask 

##results
the results are included in the following images below. the 50% percentile for June was 75, and for dec it was 71. This indicates that it is likely good to go for year round business, further, the max year round was 83, and 85 respectivly. 

##summary
I would summize that even though temperatures recorded in December seem to vary more than those of June, December would still provide appropriate weather conditions for both surfing and demand in ice cream. The average temperatures in June and December only differ by 4 degrees, and looking at the December histogram, I feel more confident in this decision--December's median temperature, with the highest frequency recorded across a span of years, is about 72 degrees, at least double the frequency of the next highest recorded temperatures, 75 and 67 respectively. It would be ill advised to not open the surf and ice cream shop based on at first clance temperature minimums.

Before making a final deicision though, I would want to perform some additional queries to get more color on weather conditions in these two months.

For specificity, I would like to delve into the summary statistics of temperatures recorded by station for each month. This can help determine geopgraphically where in Oahu to build the prospective shop. By comparing the variances in temperatures and the frequencies recorded, we can narrow in on an optimal location.
Stations vs Temps for June and December Starting Point
station_temps

Secondly, I would like to review other important variables that are correlated with optimal beach and surfing weather. Sunch varibles include precipitation, wave swells and wind condition. Though there may be some contrasting optimal conditions based on surfing vs sunbathing, it is important to identify those conditions and see how they correlate to foot traffic to the beach (depending on the time of year). It would be foolish to only value temperatures as the key indicator for opening a business.

###summary statistics images
JULY 
![step 4 chart](https://user-images.githubusercontent.com/100965117/170839682-4865968b-f330-40c5-9040-5ac267a00e99.PNG)

DEC
![Dec summary stats](https://user-images.githubusercontent.com/100965117/170839684-e4cbf3fe-7f41-450e-a855-224379416056.PNG)

