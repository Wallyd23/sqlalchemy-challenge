# sqlalchemy-challenge
# Overview

This project performs a climate analysis on the historical weather data in Honolulu, Hawaii, and sets up a Flask API to serve the analysis results. The analysis includes precipitation and temperature data, with routes to access specific datasets.

## Project Structure

├── app.py # Main Flask application
├── climate_starter.ipynb # Jupyter Notebook for initial data analysis and exploration
├── hawaii.sqlite # SQLite database containing the climate data
├── README.md # Project readme file


## Setup Instructions

Access the API
Open your web browser and navigate to http://127.0.0.1:5000/ to see the available routes.

Available Routes

    /: Home page listing all available routes.
    /api/v1.0/precipitation: Returns the last 12 months of precipitation data.
    /api/v1.0/stations: Returns a list of all weather stations.
    /api/v1.0/tobs: Returns temperature observations of the most active station for the last 12 months.
    /api/v1.0/<start>: Returns the minimum, average, and maximum temperatures for all dates greater than or equal to the specified start date.
    /api/v1.0/<start>/<end>: Returns the minimum, average, and maximum temperatures for dates between the specified start and end dates.

