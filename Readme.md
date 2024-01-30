# Weather Information Retrieval

## Introduction
This Python script retrieves and speaks the current temperature of a specified location using the WeatherAPI. It prompts the user to enter the name of a place, sends a request to the WeatherAPI, and then reads aloud the current temperature in degrees Celsius for the given location.

## Features
<ul>
<li><b>User Interaction: </b>The script prompts the user to enter the name of a place to get weather information.</li>
<li><b>WeatherAPI Integration: </b>Utilizes the WeatherAPI to fetch real-time weather data for the specified location.</li>
<li><b>Text-to-Speech: </b>Utilizes the win32com.client library to convert the weather information into speech, making it accessible audibly.</li>
</ul>

## Usage
<ul>
<li><b>Install Required Libraries: </b>Ensure that the required libraries are installed before running the script.</li>
<li><b>Run the Script: </b>Execute the script in a Python environment.</li>
  <li><b>Enter Place: </b>When prompted, enter the name of the place for which you want to retrieve weather information.</li>
  <li><b>Output: </b>The script will print the current temperature for the specified location and also read it aloud using text-to-speech.</li>
</ul>

## Customization
<ul>
<li>API Key: Replace the placeholder API key in the url variable with your own WeatherAPI key.</li>
<li>Text-to-Speech Voice: Customize the voice or other parameters for text-to-speech using the win32com.client library.</li>
</ul>

## Notes
<li>Ensure that the computer has internet access to make the API request.</li>
<li>The WeatherAPI key is essential for accessing real-time weather data.</li>
