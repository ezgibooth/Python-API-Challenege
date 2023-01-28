# Part 1: WeatherPy

In this Challenge, a Python script is created to visualize the weather of over 500 cities of varying distances from the equator. You'll use the citipy Python library Links to an external site., the OpenWeatherMap API Links to an external site., and your problem-solving skills to create a representative model of weather across cities.

The code generates random geographic coordinates and the nearest city to each latitude and longitude combination is provided.

## Deliverable 1: 
Plots to Showcase the Relationship Between Weather Variables and Latitude are created. To do this, OpenWeatherMap API is used to retrieve weather data from the cities list generated in the starter code. 

Next, a series of scatter plots to showcase the following relationships are created:

    - Latitude vs. Temperature

    - Latitude vs. Humidity

    - Latitude vs. Cloudiness

    - Latitude vs. Wind Speed

## Deliverable 2: 
Compute Linear Regression for Each Relationship
The linear regression for each relationship is calculated. Plots are separated into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). 

A series of scatter plots are created including the linear regression line, the model's formula, and the r values.


    - Northern Hemisphere: Temperature vs. Latitude

    - Southern Hemisphere: Temperature vs. Latitude

    - Northern Hemisphere: Humidity vs. Latitude

    - Southern Hemisphere: Humidity vs. Latitude

    - Northern Hemisphere: Cloudiness vs. Latitude

    - Southern Hemisphere: Cloudiness vs. Latitude

    - Northern Hemisphere: Wind Speed vs. Latitude

    - Southern Hemisphere: Wind Speed vs. Latitude

After each pair of plots, linear regression model is discussed and any relationships observed are noted.

# VacationPy

In this deliverable, Jupyter notebooks, the geoViews Python library, and the Geoapify API are used to plan future vacations. 

The code needed to import the required libraries and load the CSV file with the weather and coordinates data for each city created in Part 1 is provided to help you get started.

The main goal is to use the Geoapify API and the geoViews Python library and employ your Python skills to create map visualizations.

A map is created that displays a point for every city in the city_data_df DataFrame as shown in the following image. The size of the point should be the humidity in each city.

The DataFrame is then narrowed down to ideal weather conditions.

A new DataFrame called hotel_df to store the city, country, coordinates, and humidity.

For each city, Geoapify API is used to find the first hotel located within 10,000 meters of your coordinates.

The hotel name and the country is added as additional information in the hover message for each city on the map.