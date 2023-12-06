# python-api-challenge1
Assignment6
Part 1: WeatherPy
Overview
In this project, I aim to visualize the weather patterns of over 500 cities with varying distances
from the equator. 

Code Structure
The WeatherPy.ipynb Jupyter notebook provided in the starter code ZIP file is used.
The code generates random geographic coordinates and finds the nearest city to each latitude and
longitude combination using the citipy library.
The OpenWeatherMap API is utilized to retrieve weather data from the cities list.
The notebook guides through the process of creating scatter plots to showcase the  relationships
between latitude and various weather variables:
Latitude vs. Temperature
Latitude vs. Humidity
Latitude vs. Cloudiness
Latitude vs. Wind Speed
Linear regression is computed for each relationship, and plots are separated into 
Northern Hemisphere and Southern Hemisphere.
After each pair of plots, the notebook explains what the linear regression is modeling, 
describes any relationships noticed, and highlights other findings.

Part 2: VacationPy
Overview
In this part of the project, I utilized our weather data skills to plan future vacations. 
With using Jupyter notebooks, the geoViews Python library, and the Geoapify API.

Code Structure
The VacationPy.ipynb starter code is used to complete the following steps:
Create a map that displays a point for every city in the city_data_df DataFrame. The size of 
the point should be the humidity in each city.Narrow down the city_data_df DataFrame to find ideal weather conditions, e.g., max temperature lower than 32 degrees but higher than 21, wind speed less than 20 m/s, cloudiness <=50.
Created a new DataFrame called hotel_df to store city, country, coordinates, and humidity.
For each city, used the Geoapify API to find the first hotel located within 10,000 meters of the coordinates. 
No one hotels was found. 
Conclusion
This project combines weather data analysis, visualization, and vacation planning using various Python libraries and APIs. The code is structured to provide clear insights into weather patterns and assist in making informed decisions for future vacations.






