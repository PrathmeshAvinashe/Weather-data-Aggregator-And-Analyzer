# Weather Data Aggregator and Analyzer

## Overview
This Python application fetches weather data at regular intervals from a public API and stores it in a local SQLite database. It provides functionality to analyze and visualize trends in temperature, humidity, and wind speed over time.

## Requirements
- Python 3.x
- Libraries: `requests`, `sqlite3`, `pandas`, `matplotlib`, `schedule`

## Installation
1. Clone the repository or download the source code.
2. Install required Python libraries:
    ```
    pip install requests sqlite3 pandas matplotlib schedule
    ```
3. Get your API key from OpenWeatherMap or any other weather API provider.

## Usage
1. **Set Up API Key**: Replace `your_api_key` in the Python script with your actual API key.
2. **Run the Script**: 
    ```
    python weather_data_aggregator.py
    ```
    The script will fetch weather data at hourly intervals and store it in the SQLite database.

3. **Analyze Data**: 
    - The data is stored in the SQLite database (`weather_data.db`).
    - You can run the `analyze_weather_data()` function to visualize temperature and humidity trends.

## Example Output
- Hourly weather data is stored and visualized with temperature and humidity trends shown in line charts.

