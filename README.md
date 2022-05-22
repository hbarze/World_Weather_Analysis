# World_Weather_Analysis
 Module 6
 
## Overview
Using Python, Pandas, Matplotlib, Jupyter Notebook, Google APIs, and JSON to complete the following: 
* Add weather descriptions to weather data created in the module
* Use input statements to filter data for weather preferences, which then will be used to identify potential travel destinations and nearby hotels
* From the potential travel destinations list, choose four cities to create a travel itinerary
* Using Google Maps Directions API, create a travel route between the four cities as well as a marker layer map

## Results

### Weather Data
Based on 2,000 random latitude and longitudes, I used the Open Weather Map and retrieved the information with an API code, and then cleaned the data and saved it into a DataFrame. 

<img width="536" alt="Screen Shot 2022-05-22 at 4 54 35 PM" src="https://user-images.githubusercontent.com/96043107/169717571-f2c6c966-75d9-4aa2-a8ad-b0398fda501b.png">

### Travel Destination Map
After using an input statement to filter data for the customer's weather preferences, travel destinations and hotels were identified with a marker layer map and markers.

<img width="1351" alt="WeatherPy_vacation_map" src="https://user-images.githubusercontent.com/96043107/169717648-83df23fe-c2b8-4744-be02-f11f27cbd1c3.png">

### Travel Itinerary Map
Finally, using Google Directions API, I created a travel itinerary map that forms a route for the 4 different vacation locations.

![WeatherPy_travel_map](https://user-images.githubusercontent.com/96043107/169717684-84c342d2-4163-46bf-8118-b4fd7a019f2e.png)
