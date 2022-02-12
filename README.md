# World Weather Analysis

## Project Overview

### Purpose
Assisting the head of analysis for the user interface team, Jack, from PlanMyTrip app to collect and present data for customers via the search page, which they then filter based on their preferred travel criteria in order to find their ideal hotel anywhere. After the beta test, we got positive feedbacks from the testers with some recommendations. Based on their request we will try to add the weather description to the weather data, providing more straight forward weather information. Then choose the best four potential cities for a vacation based on certain weather criteria and beta testers' preference. Meanwhile map and route these cities to help travelers find their ideal vacation plan. 

## Resources
- Data Source: [OpenWeatherMap API's](https://openweathermap.org/), [Google Cloud Platform (Google Maps Platform)](https://cloud.google.com/)
- Software: Python 3.10.1, Jupyter Notebook

## Results
- We increase our weather database from 1,500 random latitudes and longitutdes to 2,000, which truned to 691 nearest cities.
- According to beta test, travelers prefer a warm trip so we set a temperature range between 70 °F and 90 °F for this result presentation.   <p align="center">
  <img src="https://github.com/Jarviniazh/Module-6-Challenge-World-Weather-Analysis/blob/main/Vacation_Search/WeatherPy_vacation_map.png?raw=true" alt="WeatherPy_vacation_map"/>
   </p>  
 
 - Take one user who would like to visit Australia as an example, the app select four potential cities (Sydney, Ballina, Katherine, Geraldton) based on the information he/she entered on the search page. And then plan an ideal route as reference.
  <p align="center">
  <img src="https://github.com/Jarviniazh/Module-6-Challenge-World-Weather-Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png?raw=true" alt="WeatherPy_travel_map"/>
  </p>  
  
  - If the user is satisfied with the recommended route, he/she could also get all detailed destination info back, including hotel name, city, country and current weather description.   
  <p align="center">
  <img src="https://github.com/Jarviniazh/Module-6-Challenge-World-Weather-Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png?raw=true" alt="WeatherPy_travel_map_markers"/>
  </p> 
