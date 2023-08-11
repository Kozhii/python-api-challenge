# python-api-challenge

For this challenge we worked with API's from Geoapify and OpenWeathermap to viluaize and analyze over 500 cities around the equator. 

We generated a series of scatter plots to demonstrate the connections between:
  -The city's latitude and its temperature
  -The city's latitude and its humidity level
  -The city's latitude and the amount of cloudiness
  -The city's latitude and the speed of the wind

  We then computed the linear regression for each relationship and seperated it by northern and southern hemispheres.

We created a map that displays a point for every city in the city_data_df DataFrame. We then narrowed it down to find the ideal weather condition. Following we created a new DataFrame called hotel_df to store the city, country, coordinates, and humidity. For each city,  we used the Geoapify API to find the first hotel located within 10,000 meters of your coordinates. We finished by adding the hotel name and the country as additional information in the hover message for each city on the map.
