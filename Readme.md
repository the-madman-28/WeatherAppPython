# Weather Information Retrieval

## Introduction
This Python script retrieves and speaks the current temperature of a specified location using the WeatherAPI. It prompts the user to enter the name of a place, sends a request to the WeatherAPI, and then reads aloud the current temperature in degrees Celsius for the given location.

## Features
- **User Interaction:** The script prompts the user to enter the name of a place to get weather information.
- **WeatherAPI Integration:** Utilizes the WeatherAPI to fetch real-time weather data for the specified location.
- **Text-to-Speech:** Utilizes the win32com.client library to convert the weather information into speech, making it accessible audibly.

## Usage
1. **Install Required Libraries:** Ensure that the required libraries are installed before running the script.
2. **Run the Script:** Execute the script in a Python environment.
3. **Enter Place:** When prompted, enter the name of the place for which you want to retrieve weather information.
4. **Output:** The script will print the current temperature for the specified location and also read it aloud using text-to-speech.

## Customization
- **API Key:** Replace the placeholder API key in the url variable with your own WeatherAPI key.
- **Text-to-Speech Voice:** Customize the voice or other parameters for text-to-speech using the win32com.client library.

## Notes
- Ensure that the computer has internet access to make the API request.
- The WeatherAPI key is essential for accessing real-time weather data.
