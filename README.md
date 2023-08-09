# python-api-challenge

## Contributor: Lan "Alice" Nguyen

This repository contains the code and visualizations for the WeatherPy and VacationPy assignments. The assignment consists of two Jupyter Notebook files: WeatherPy.ipynb and VacationPy.ipynb.

### WeatherPy.ipynb

In this notebook, the following steps were performed:

- More than 500 random cities were generated.
- Information such as maximum temperature, humidity, cloudiness, and wind speed were retrieved for each city using OpenWeatherMap API.
- Scatter plots were created to showcase the relationships between latitude and the following weather parameters:
  - Latitude vs. Temperature
  - Latitude vs. Humidity
  - Latitude vs. Cloudiness
  - Latitude vs. Wind Speed
- The plots were divided into the Northern Hemisphere and Southern Hemisphere.
- Linear regression lines were fitted to each scatter plot, and the model's formula and the r-value were displayed on the plots.

### VacationPy.ipynb

In this notebook, the following steps were performed:

- A subset of cities from the WeatherPy dataset was selected based on certain ideal weather conditions.
- For each selected city, the Geoapify API was used to find the nearest hotel within 100,000 meters of the city's coordinates.
- The cities and their corresponding hotels were plotted on a map using GeoViews Python library.

