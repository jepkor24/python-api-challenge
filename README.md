Weather PY
Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude
To fulfill the first requirement, you'll use the OpenWeatherMap API to retrieve weather data from the cities list generated in the starter code. Next, you'll create a series of scatter plots to showcase the following relationships:

Latitude vs. Temperature

Latitude vs. Humidity

Latitude vs. Cloudiness

Latitude vs. Wind Speed

Requirement 2: Compute Linear Regression for Each Relationship
To fulfill the second requirement, compute the linear regression for each relationship. Separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude). 
Defined a function in order to create the linear regression plots below:
Northern Hemisphere: Temperature vs. Latitude

Southern Hemisphere: Temperature vs. Latitude

Northern Hemisphere: Humidity vs. Latitude

Southern Hemisphere: Humidity vs. Latitude

Northern Hemisphere: Cloudiness vs. Latitude

Southern Hemisphere: Cloudiness vs. Latitude

Northern Hemisphere: Wind Speed vs. Latitude

Southern Hemisphere: Wind Speed vs. Latitude
Provide an analysis of the findings based on r-squared what type of relationship the variables have for each of the hemispheres i.e. Northern and Southern Hemisphere

Vacation PY
Create a map that displays a point for every city in the city_data_df DataFrame as shown in the following image. The size of the point should be the humidity in each city.

Narrow down the city_data_df DataFrame to find your ideal weather condition. For example:

A max temperature between 25 to 33 celcius or 298 to 306 kelvin

Wind speed between 0-15 m/s

humidity between 65-72 %

Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.

For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.

Add the hotel name and the country as additional information in the hover message for each city on the map

