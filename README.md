# World_Weather_Analysis

## A. Collect the Data

* Use the NumPy module to generate more than 1,500 random latitudes and longitudes.
* Use the citipy module to list the nearest city to the latitudes and longitudes.
* Use the OpenWeatherMap API to request the current weather data from each unique city in your list.
* Parse the JSON data from the API request.
* Collect the following data from the JSON file and add it to a DataFrame:
    1) City, country, and date
    2) Latitude and longitude
    3) Maximum temperature
    4) Humidity
    5) Cloudiness
    6) Wind speed

## B. Exploratory Analysis with Visualization

*   Create scatter plots of the weather data for the following comparisons:
    1) Latitude versus temperature
    2) Latitude versus humidity
    3) Latitude versus cloudiness
    4) Latitude versus wind speed
    
*   Determine the correlations for the following weather data:
    1) Latitude and temperature
    2) Latitude and humidity
    3) Latitude and cloudiness
    4) Latitude and wind speed
    
*   Create a series of heatmaps using the Google Maps and Places API that showcases the following:
    1) Latitude and temperature
    2) Latitude and humidity
    3) Latitude and cloudiness
    4) Latitude and wind speed

## C. Visualize Travel Data
Create a heatmap with pop-up markers that can display information on specific cities based on a customer's travel preferences. Complete these steps:
    1)  Filter the Pandas DataFrame based on user inputs for a minimum and maximum temperature.
    2)  Create a heatmap for the new DataFrame.
    3)  Find a hotel from the cities' coordinates using Google's Maps and Places API, and Search Nearby feature.
    4)  Store the name of the first hotel in the DataFrame.
    5)  Add pop-up markers to the heatmap that display information about the city, current maximum temperature, and a hotel in the city.
