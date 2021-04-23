# python-api-challenge

## WeatherPy (jupyter notebook)
Weather data was collected for 500+ random cites generated from a random selection of latitude and longitude pairs.

The follow graphs were then generated with the data:
- Max Temperature vs. Latitude
- Humidity vs. Latitude
- Cloudiness vs. Latitude
- Wind Speed vs. Latitude

Another set of graphs were created but the cities were split between northern and southern hemisphere graphs. These graphs also had linear regression performed on them and the r-squared value calculated.

Three trends are listed at the end of the WeatherPy jupyter notebook.

NOTE: All graphs and a list of the cities' weather can be found in the weather_data directory. 

## VacationPy (jupyter notebook)
The cities' weather data collected in the WeatherPy notebook was then narrowed down to cities with perfect weather conditions (70-78 F, less than 10 mph of wind, and no clouds).

Hotels were found in these cities with Google's PLaces API and added to a map along with a heat map based on how humid all the cities found in the WeatherPy were with the use of Google's Google Maps API. 

NOTE: A screenshot of the map generated can be found in the travel_map directory. 
