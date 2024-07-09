# python-api-challenge
module 6 challenge


## WeatherPy
- Creates dataset for cities based on random latitiude and longitude values and locates the nearest city.
- Updates latitude and longitude points once the closest city has been identified, using the [Geoapify API](https://apidocs.geoapify.com/docs/places/#about).
- Uses the [Weather API](https://openweathermap.org/api/one-call-3) to get weather information based on the identified latitude and longitude points.
- Created graphs for:
    - Latitude vs. Temperature
    - Latitude vs. Humidity
    - Latitude vs. Cloudiness
    - Latitude vs. Wind Speed
 - Created scatter plots with linear regression lines to assess the relationships between each of the following:
     - Temperature vs. Latitude
     - Humidity vs. Latitude
     - Cloudiness vs. Latitude
     - Wind Speed vs. Latitude


### VacationPy
- Uses the city dataset created in the WeatherPy file to create a map with all locations identified in a map.
- Creates an ideal weather dataset for a vacation spot and then identifies a hotel in a 10,000 meter radius of the city, if on exists.


## Resources
- Code Files: Both code files are located in the [WeatherPy Folder](https://github.com/megan-oconnor/python-api-challenge/tree/main/WeatherPy)
- Datasets: 1 datasets for the city data was created; it's located in the [output_data folder](https://github.com/megan-oconnor/matplotlib-challenge/tree/main/data) folder
- Images: contain screenshots of the the graphs output, all located in the [output_data folder](https://github.com/megan-oconnor/matplotlib-challenge/tree/main/Images) folder
- APIs used:
    - [Geoapify API](https://apidocs.geoapify.com/docs/places/#about)
    - [Weather API](https://openweathermap.org/api/one-call-3)
