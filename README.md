# Weather Proyect

This proyect consists of the following technical analyses:

1. Weather Data Retrieval (Weather_Database)
2. Customer Travel Destination Maps (Vacation_Search)
3. Travel Itinerary Map (Vacation_Itinerary)

## Weather Data Retrieval

The Weather Data Retrieval analysis generates a set of 2,000 random latitudes and longitudes, retrieves the nearest city for those latitudes, and performas API calls with the OpenWeatherMap. Using the API information, the current weather information is retrieved for each city and stored in a DataFrame.

## Customer Travel Destination Maps

The Customer Travel Destination Maps analysis uses input statements to retrieve customer weather preferences, then uses those preferences to identify potential travel destinations and nearby hotels. The destinations are shown on a marker layer map with pop-up markers.

## Travel Itinerary Map

The Travel Itinerary Map analysis uses the Google Directions API to create a travel itinerary that shows the route between four cities. A marker layer map with a pop-up marker for each city on the itinerary is a created.
