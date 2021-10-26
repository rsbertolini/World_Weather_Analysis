# World_Weather_Analysis

## Purpose of Project
There were 3 main components of the WeatherPy challenge.
1.  Generate an array of random latitude and longitude coordinates.  Using the coordinates and citipy function, locate the nearest city.  Call the Open Weather API for current weather data and export that data to a CSV file.
2.  Using 2 user inputs for min and max temperature, read in the CSV file from step 1 and narrow down the list to preferred cities that meet the temperature range from the user.  Using Google Places API get hotel info for those cities and export the city-hotel data to another CSV file.
3.  Using the city-hotel data from Step 2, choose 4 cities within the same country and use Google Directions API to map a roundtrip route between the 4 cities.  Create a map with a direction layer and a marker layer.
