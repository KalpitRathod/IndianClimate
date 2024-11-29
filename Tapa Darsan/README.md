# Tāpa-Darśan (ताप-दर्शन) - Vision of Heat

## Overview
**Tāpa-Darśan** (ताप-दर्शन) is a project designed to measure, monitor, and track the real-time temperature of every city across India. With the aim of providing accurate and up-to-date temperature data, this project will serve as a platform for understanding the climate variations throughout the country. 

The project uses a combination of weather data APIs, real-time data fetching, and cloud-based storage to continuously update and present the temperature information, offering insights into climate trends and helping decision-makers in various sectors.

## Data Collection
- **Daily Temperature - 70 years Data for Major Indian Cities**: Historical data taken from [Open City-Urban Data Portal](https://data.opencity.in/dataset/daily-temperature-70-years-data-for-major-indian-cities)

## Features
- **Real-Time Temperature Tracking**: Get live updates of the temperature for each city in India.
- **Data Visualization**: View interactive graphs and heatmaps for temperature patterns.
- **City-wise Temperature Data**: Monitor temperatures for multiple cities, with the ability to search by city name.
- **Historical Data**: Analyze past temperature trends to understand the variation over time.
- **Scalable Infrastructure**: Designed to handle the vast number of cities and real-time data updates.

## Technologies Used
- **Weather APIs**: OpenWeatherMap, Weatherstack, or Climacell for real-time weather data collection.
- **Backend**: Python, with libraries such as Pandas, NumPy for data processing and storage.
- **Cloud Storage**: Firebase, AWS DynamoDB, or Google Cloud for real-time data storage and retrieval.
- **Front-End**: React.js or HTML/CSS/JS for the web interface; Google Maps API or Leaflet.js for displaying city locations.
- **Data Visualization**: Matplotlib, Plotly for creating dynamic charts and graphs.
- **Task Scheduling**: Cron jobs or similar techniques to fetch and update temperature data at regular intervals.

Feel free to modify the installation and usage instructions based on your project specifics, like the exact API you use and any unique setup details.
