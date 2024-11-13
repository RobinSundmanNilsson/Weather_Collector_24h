# Weather Collector 24h

## Description

This Python program retrieves and displays weather forecasts from the SMHI (Swedish Meteorological and Hydrological Institute) and YR (Norwegian Meteorological Institute) APIs. Users can select to fetch or display weather data from either SMHI, YR, or both. The program extracts relevant weather parameters, including temperature and precipitation probability, and saves the forecasts as Excel files for easy reference.

## Features

Menu Interface: Navigate options to retrieve or display weather forecasts from SMHI, YR, or both sources.

Data Collection: Fetches the latest 24-hour forecast for a specified location, set by latitude and longitude.

Excel Export: Saves weather data in Excel format for both SMHI and YR forecasts.

Data Display: Outputs a formatted view of the forecast directly to the console.

## Requirements

Libraries: requests, pandas, openpyxl and datetime.

User Agent: Includes a custom User-Agent header for accessing the YR API.

This program is designed for users interested in automated, quick-access weather forecasts, with easy-to-read data storage and retrieval options.
