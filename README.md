# python-projects

## BMI Calculator
This Python code is a Body Mass Index (BMI) calculator. It takes your weight in kilograms and height in meters as input, then calculates your BMI and classifies it into a health category.

Here's a quick breakdown:

calculate_bmi(weight, height): This function computes your BMI using the standard formula. categorize_bmi(bmi): This function takes the calculated BMI and tells you if you're Underweight, Normal weight, Overweight, or in the Obesity range. The main part of the script prompts you for your weight and height, handles potential errors if you enter non-numeric values, and then displays your BMI and its corresponding category.

## Customizable Password Generator
This Python script is a password generator that creates strong, random passwords based on your specific criteria.

Here's a quick rundown of what it does:

generate_password(...) Function: This function is the core of the tool. It builds a pool of characters (uppercase, lowercase, numbers, and special symbols) based on your selections. It then picks random characters from this pool to create a password of your desired length. User Customization: The script prompts you to choose: The length of the password. Whether to include uppercase letters, lowercase letters, digits, and special characters. Error Handling: It ensures you select at least one character type to generate a valid password. Essentially, this tool helps you create secure and unique passwords tailored to your needs.

## Weather Application
This Python script is a command-line weather application that fetches and displays current weather information for any city worldwide, offering unit customization and robust error handling.

Here's a concise overview:

get_weather_data(city_name, unit_preference): This function is the core of the application. It uses the OpenWeatherMap API to retrieve weather data for a specified city. It supports both Imperial (Fahrenheit) and Metric (Celsius) units and includes extensive error handling for network issues, invalid API keys, and cities not found. display_weather_info(...): This function takes the raw weather data and presents it to the user in a readable, formatted way, including temperature, "feels like" temperature, humidity, wind speed, and pressure, with appropriate unit symbols. main(): This function orchestrates the user interaction. It prompts the user for a city name and their preferred units, then calls the get_weather_data and display_weather_info functions to provide the weather report. It runs in a loop, allowing continuous lookups until the user chooses to exit. In short, this is a user-friendly and reliable tool for getting current weather conditions directly from your terminal.
