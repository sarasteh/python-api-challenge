# python-api-challenge

## WeatherPy
Here I created a Python script to visualize the weather of over 500 cities of varying distances from the equator. I used the citipy Python library the OpenWeatherMap API calls. Using the *the citipy Python library* I generated random geographic coordinates and the nearest city to each latitude and longitude combination. Then I used the OpenWeatherMap API to retrieve weather data from the cities and  create a series of scatter plots to showcase the following relationships:

- Latitude vs. Temperature

- Latitude vs. Humidity

- Latitude vs. Cloudiness

- Latitude vs. Wind Speed

Next I separated the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude) and draw the regression line for each plots in Northern Hemisphere and Southern Hemisphere. The model'formula and the r_value has been shown on the plot. 


## VacationPy
for this part, I used the cities found in WeatherPy as an input csv file. Then I narrowed down the cities to find my ideal weather condition. For example:

- A max temperature lower than 26 degrees but higher than 14

- Wind speed less than 5.5 m/s

- Zero cloudiness  

For each city, I used the Geoapify API to find the first hotel located within 10,000 meters of the desired coordinates.
Using the *Geoapify API and the geoViews Python library* I created map visualizations. I also added the hotel name and the country 
as additional information in the hover message for each city on the map.

> --------------------------
The **WeatherPy folder** includes:
- Two python files:
  - WeatherPy
  - VacationPy
- output_data
  - cities.csv
  - Plots created in WeatherPy



 
