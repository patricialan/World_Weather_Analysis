# World_Weather_Analysis

## Project Summary
- Weather data for 550 cities was collected into a DataFrame using the OpenWeatherMap's "current weather data" API and the citipy module. 
- For a client's weather preferences (temperature, rainfall, and snowfall), a DataFrame was created listing hotels in cities that fulfil the weather criteria. A layer map was also created with a pop-up marker for each hotel that included location and weather information. Google Maps' "Places API" was used.
- For a driving trip through 4 cities, a directions layer map was created using Google Maps' "Directions API" and a marker layer map was also created. Pop-up markers showed location and weather information for the 4 cities. 

## Resources
- Software: Jupyter Notebook 6.0.3, conda 4.8.2, Python 3.8.2, pandas 1.0.3, and NumPy 1.18.1, OpenWeatherMap's current weather data API, citipy 0.0.5, Google Maps' Places and Directions APIs