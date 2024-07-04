# Preview
![mich](https://github.com/m1chtv/mich-weather-app/assets/72360802/7f57e6eb-7524-4256-baff-08aab0126c1e)

# mich Weather App
Description: This program is a weather application that fetches weather information from an API and displays it using a Tkinter-based graphical user interface (GUI). It allows users to search for weather information of a specific location by entering the city name.

## File Structure:
- mich.py: The main Python script that contains the application logic and GUI components.

## Functionality:
1. GUI Design:
   - The program uses Tkinter to create a simple and intuitive graphical interface.
   - It includes a text entry field for users to enter the city name.
   - A search button triggers the API request to fetch weather data.
   - Weather information is displayed in a visually appealing format.

2. API Integration:
   - The program utilizes the Requests module to send HTTP requests to an external weather API.
   - It fetches weather data in JSON format.

3. Weather Data Display:
   - The JSON response from the API is parsed using the JSON module to extract relevant weather information.
   - The program displays the fetched data, including current temperature, weather description, humidity, wind speed, etc.
  
4. Error Handling:
   - The program handles potential errors, such as invalid input, network issues, or unavailable API responses.
   - Error messages are displayed to guide the user and ensure smooth program execution.

## Usage:
1. Run the mich.py script using Python 3.x.
2. Enter the name of the city for which you want to check the weather.
3. Click the "Search" button.
4. The program will fetch weather data from the API and display it on the GUI.

## Note:
- You need an internet connection for the program to access the weather API.
- Ensure that all dependencies are installed before running the script.

## Improvements and Extensions:
- The program can be enhanced to include additional features such as extended forecasts, weather alerts, or interactive maps.
- Error handling can be further improved by providing more informative error messages.
- The GUI can be customized to match specific design requirements.
