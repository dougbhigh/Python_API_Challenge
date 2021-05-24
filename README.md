# VacationWeather
Part 1 WeatherPy (and WeatherPyLg with larger dataset)
- randomly generate geo-coordinatese, use citypy to find nearest city.
- call openweather to get weather data for cities where available.
- store data to dataframe and create plots for various weather conditions vs latitudes.
- write out dataframe and charts (as png files).

Part 2 VacationPy
- read in WeatherPy dataframe and create interactive heat map of globe showing humidity levels.
- find potential vacation cities based on temperature, humidity, and cloudiness.
- call google to find hotels near criteria cities.
- add popup markers to map with hotel information.

WeatherPyLg
- copy of WeatherPy with 15,000 initial points resulting in 2907 cities, 2699 of which had weather data (compared to 1500, 622, and 568 in original run).    

![alt text](https://github.com/dougbhigh/Python_API_Challenge/blob/master/WeatherPy/output_data/lat_vs_humid.png)
![alt text](https://github.com/dougbhigh/Python_API_Challenge/blob/master/WeatherPy/output_data/south_lat_vs_maxtemp.png)
![alt text](https://github.com/dougbhigh/Python_API_Challenge/blob/master/WeatherPy/output_data/Screenshot.png)