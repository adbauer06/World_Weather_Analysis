# World_Weather_Analysis

## Project Overview
The purpose of this project was threefold:

1.  Retrieve weather data for a set of random cities
1.  Create a Customer Travel Destinations Map
1.  Create a Travel Itinerary Map


##  Resources
- Software:  Jupyter Notebook, Visual Studio Code, 1.58.2
- APIs: OpenWeatherMap, Google Maps and Places, Google Directions


## Project Results

### Retrieve Weather Data
For this task, 2000 random latitude/longitude combinations were generated.  We then retrieved the nearest city to those that we could.  For those cities that were found, the OpenWeatherMap API was used to retrieve the current weather conditions, including percent humidity, percent cloudiness, wind speed, and weather description.  This data was then saved to a file and exported to a csv file.

### Create a Customer Travel Destinations Map
For this task, input statements were used to retrieve weather preferences based on preferred temperatures.  Using the file created in the previous task, cities with matching temperature preferences were identified.  A search was then performed using google maps and places API to find nearest hotels to those locations.  This data was saved to a dataframe and exported to a csv file.  A marker layer map was created with the hotels marked.  Pop-up boxes were added to the markers to give information such as hotel name, locaiton, and current weather information.

### Create a Travel Itinerary Map
For this task, four cities were selected from our data in the previous task to create a travel itinerary using the Google Directions API.  A marker layer map was also created showing these four cities and their pop-up description on a map.

