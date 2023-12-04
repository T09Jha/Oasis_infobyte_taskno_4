# Oasis_infobyte_taskno_6
# WEATHER APP

# LANGUAGE AND LIBRARIES

- Python
- Tkinter
- Requests
- Datetime
- Matplotlib

# FEATURES

- Takes input for a City
- Gives the weather details for the city
- Gives the recorded details of hourly tempratures.
- Provides temprature in both celsius and fahrenheit
- Maps the hourly tempratures which give accurate weather details
- Gives wind speed of the city
- Gives humidity content of the city

# FUNCTIONS AND GUI ITEMS

- get_weather
- get_weather_for_city
- plot_line_graph
- Weather App Window
- "Enter city name:" label
- city_entry
- celsius_button
- fahrenheit_button
- unit_var.set("metric")  

# EXPLAINATION 

We import necessary libraries, including requests for API requests, tkinter for GUI, Label, Entry, Button, Radiobutton, and StringVar for creating GUI components, and matplotlib.pyplot for plotting graphs.
From the website: https://openweathermap.org/api , we generate an API key for accessing the OpenWeatherMap API is stored in this variable.
The get_weather() function sends a request to OpenWeatherMap's forecast endpoint with the provided API key and city name. It retrieves temperature, humidity, and wind speed data for the next few hours.
The get_weather_for_city() function is called when the "Get Weather" button is clicked. It retrieves weather data using the get_weather function and updates the GUI with the temperature graph and additional information.
Using the matplotlib and datetime library and the plot_line_graph() function we plot a line graph between the date and time stamp and the temprature in degree fahrenheit and celsius.
There are two radio buttons for selecting the temperature unit (Celsius or Fahrenheit).
Labels, Entry widget, and Button for inputting the city name and triggering the weather retrieval.
The result_label is used to print the wind_speed and humidity of the city.
