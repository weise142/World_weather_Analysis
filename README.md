# World Weather Analysis
## Overview
This project analyses weather patterns around the globe to offer insights to traverlers who want to book a trip. I started this analysis by using the Open Weather Map API to pull weather data from over 730 different cities around the world. The data consists of the the following data points:
- Maximum Temperature
- Cloudiness
- Wind Speed
- Humidity
- Current Weather Description
This information is pulled into a database to make it easier for travelers to filter vacation options in search of their ideal conditions. I then use this database to create a vacation search code and map that will provide travelers with their ideal vacation destinations based on the weather criteria entered. The below map shows vacation destinations with Maximum Temperatures between 78 and 80 degrees:
![This is an image](https://github.com/weise142/World_weather_Analysis/blob/main/markers%20filtered%20by%20temp.png)
## Vacation Itinerary
Another code and mapping option was created using this weather database as well. With the use of Google Maps API, I created a vacation itinerary map that allows you to input cities you would like to visit and it will map out the route. Below is an image that shows a US roadtrip starting at Mayo, going to Hurricane, San Patricio, and Cheney before returning to Mayo. 
![This is an image](https://github.com/weise142/World_weather_Analysis/blob/main/roadtrip.png)
Along wth plotting cities within your ideal weather conditions, this code will also pull up hotel information in a city of your choice, as in the image below:
![This is an image](https://github.com/weise142/World_weather_Analysis/blob/main/Hotel%20info.png)
By using these tools, travelers can filter their destinations using their ideal weather conditions and then create an itinerary for their next vacation
