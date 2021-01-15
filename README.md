Created a python script to visualize the weather of 500+ cities across the world of varying distance from the equator. This uses simple python libraries(https://pypi.python.org/pypi/citipy), the [OpenWeatherMap API](https://openweathermap.org/api), and a little common sense to create a representative model of weather across world cities.

Scatterplots of the following were created:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

Scater plots with linear regression were created for Northern and Southern Hemispheres:

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude


### Part II - VacationPy

A heat map that displays the humidity for every city from the part I was created. The data was then filtered to ideal weather conditions for vacationing based on temperature, wind speed, and cloudiness.  Using Google Places API the nearest hotel of each ideal city was found and plotted on the heatmap.