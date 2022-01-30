# World Weather Analysis

## Overview
Beta testers have recommeneded a few changes to the PlanMyTrip app. One of their recommendations was adding the weather description to the weather data. We will  have the beta testers use input statements to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels. From the list of potential travel destinations, the beta tester will choose four cities to create a travel itinerary. Finally, using the Google Maps Directions API, you will create a travel route between the four cities as well as a marker layer map.

## Results
First we tried to generate  a set of 2,000 random latitudes and longitudes, retrieve the nearest city, and perform an API call with the OpenWeatherMap. In addition to the city weather data you gathered in this module, use your API skills to retrieve the current weather description for each city. Then, create a new DataFrame containing the updated weather data.

![WeatherPy_vacation_map](https://user-images.githubusercontent.com/58046234/151668726-af5e54ea-7eb7-4525-b040-a921de012a09.png)

Then, we use input statements to retrieve customer weather preferences, then use those preferences to identify potential travel destinations and nearby hotels. Then, show those destinations on a marker layer map with pop-up markers. In the picture below, we used the tempateres between 20 - 65 degrees. 

![Screenshot (5)](https://user-images.githubusercontent.com/58046234/151668932-fcdda7d7-90ec-44f6-b8e0-27d7b796aa60.png)

Finally we choosed 4 cities the customer would want to visit. We use the Google Directions API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, create a marker layer map with a pop-up marker for each city on the itinerary. Below, we did a trip starting from Blaj, RO to Asau, RO to Rokytne, UA to Steenbergen, NL.

![Screenshot (4)](https://user-images.githubusercontent.com/58046234/151668867-bbbd601d-80e7-4418-98fb-9a11d38cc153.png)


## Summary
