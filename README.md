# Weather Forecast App

## Overview
This Weather Forecast GUI app, created with Python's tkinter, fetches city weather forecasts, saves favorites, toggles between Celsius and Fahrenheit, and offers clipboard data copying. It also auto-detects the user's location for weather updates.
This Weather Forecast App is a graphical user interface (GUI) application built using the Python tkinter library. It allows users to retrieve weather forecasts for cities, save their favorite cities, and switch between temperature units (Celsius and Fahrenheit). Additionally, it offers features like copying weather data to the clipboard and detecting the user's current location for weather information.

## Key Features:

- Weather Forecast: Users can enter the name of a city and retrieve weather information, including temperature, weather conditions, wind speed, and humidity.

- City Management: Users can save their favorite cities for quick access. The saved cities are listed in a dropdown menu, and users can load their weather forecasts with a single click.

- Temperature Units: Users can switch between displaying temperatures in Celsius (°C) and Fahrenheit (°F).

- Refresh Data: The app provides a button to refresh weather data for the current city.

- Clear Data: Users can clear the displayed weather data and the input city name.

- Copy to Clipboard: Weather information can be easily copied to the clipboard for sharing or saving.

- Auto-Detect Location: The app can automatically detect the user's current location and display the weather forecast for that city.

- Visual Elements: The app features an appealing user interface with labels, buttons, and icons. Weather conditions are visually represented with icons.

- Data Persistence: The app can save the list of favorite cities to a file ('cities.txt') for future use.

## Dependencies:

+ Python
+ tkinter (for the graphical interface)
+ requests (for making API requests to obtain weather data)
+ pyperclip (for copying data to the clipboard)
+ PIL (Pillow) (for displaying weather icons)
+ The user is required to provide a valid API key for accessing weather data.

## Usage:

- Enter the name of a city in the input field and click the "Forecast" button to retrieve weather data.

- Save your favorite cities using the "Save City" button.

- Load a saved city's weather forecast by selecting it from the dropdown menu and clicking the "Load City" button.

- Switch between Celsius and Fahrenheit temperature units using the respective buttons.

- Use the "Refresh" button to update weather data for the current city.

- Clear the displayed data and input field using the "Clear" button.

- Copy weather data to the clipboard with the "Copy" button.

- Automatically detect your location and view the weather forecast using the "Detect My City" button.
