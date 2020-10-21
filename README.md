# python-api-challenge

By using a weather api and google map api, we were able to use random locations around the country to get weather data with relation to the equator for the WeatherPy part. The VacationPy code was able to isolate locations with the best weather, and then locates the closest hotel to the latitude and longitude as well.

### WeatherPy
World Cities were randomized using the Citipy library. With random cities listed, we used them to pull data from OpenWeatherMap API for over 500 cities. A loop was used to find temperature, humidity, cloudiness, and wind speed to compare it to latitude and longitude of the cities. The graphs will all be using Latitide data since we are trying to analyze the weather as we move away from the equator with scatter plots

The second part for WeatherPy was to run a linear regression for each scatter plot in both the Northern and Southern Hemispheres. Most of the data concluded that there were not much correlation between Latitude and changing data except for temperatures.

All of the graphs are located in the `output_data` folder above. The csv for the unique cities to be used in VacationPy is also in the folder.

### VacationPy