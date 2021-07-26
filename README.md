
# WeatherPy & VacationPy
![Image of weather](https://t3.ftcdn.net/jpg/02/48/62/02/360_F_248620246_GYqZEsT4LebYSiUkzfMnteGWTQKw0zg7.jpg)

Applying my knowledge in Python requests, APIs, and JSON traversals to answer fundamental questions about geographical coordinates and warm weather.
## Part 1: WeatherPy
I created a jupyter notebook to visualize the weather of 500+ cities globally. Using the Openweathermap API, I created dataframes to make observations on weather and where the respective city is located.

My analysis focuses on the correlation between latitude and temperature, humidity, cloudiness, and wind speed. 
### My observable trends:
- The most obvious trend analyzed from the weather data is that cities closest to the equator tend to be the warmest, and the cities furthest away, are the coldest.
- A suprising find is that in the southern hemisphere, there is a negative relationship between latitude and humdity. I assumed the tropical islands would make it more positive, but after my analysis it is obvious that the desert cities near the equator is what makes the correlation negative.
- There is no strong relationship between latitude and wind speed

## Part 2: VacationPy
Now utilizing the data I gather and cleaned in the first part, I will use another notebook to geocode the locations and create a heatmap layer over Google Maps.

![worldheatmap](https://user-images.githubusercontent.com/62668061/127070923-c428bf76-b48a-4526-8ce2-f11291468a42.png)

Furthermore, I will create an "ideal vacation spot" dataframe based on what constitutes good weather, to find vacation destinations. The heatmap will then have distinct markers with cities that fit the ideal vacation weather criteria and have a nearby hotel


![hotel-heatmap](https://user-images.githubusercontent.com/62668061/127070867-0ab5e5a7-296b-4b5d-82dc-2319fdf77db1.png)
