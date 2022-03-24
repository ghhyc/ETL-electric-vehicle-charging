# US emissions and electric vehicle

Explore the relationship of US emissions and electric vehicle.

## Overview:

Analysis to show the states CO2 levels compare across the U.S and how many states are adopting electric vehicles by counting the number charging station installations.

## Project Outline:

### Data Collection:

- Sources:
  - [US and world CO2 emission](https://www.kaggle.com/manchunhui/world-co2-emissions-analysis) -.csv format
  - States CO2 emission - .csv format
  - [EV Charging Station](https://afdc.energy.gov/fuels/electricity_locations.html#/find/nearest?fuel=ELEC) - .json format

### Data Munging:

- Cleaned and consolidated the US, State emission and electric vehicle location data by Jupyter Notebook.
- Imported and cleaned data file to PostregSQL by using Jupyter Notebook.
- Database was created in SQLite with Flask route to store the aggregate data.

### Data Visuals:

- Used Leaflet and D3 to generated the visuals from database.
- Used Python Flask, API, HTML/CSS, JavaScript for creating a webpage and display visualizations graph.
- Deploy app to Heroku:

### US map and EV station:

![US map and EV station](https://github.com/ghhyc/electric-vehicle-charging/blob/main/images/us_map.jpg)
