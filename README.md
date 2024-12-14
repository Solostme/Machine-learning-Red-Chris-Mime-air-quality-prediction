# Machine-learning-Red-Chris-Mine-air-quality-prediction
This project aims to predict the air quality in the Red Chris Mine mining area, focusing on analyzing the impact of major pollutants (such as PM2.5, O3, NO2, CO2, SO2, CO and PM10) and weather conditions on the mine area's air quality index (AQI). The project obtains and saves real-time air and weather data and uses machine learning models to provide high-precision air quality forecasts for the mine area.

## Objectives
1. Build an efficient ETL pipeline to extract air quality data from Ambee.  
2. Use Python and Power BI to visualize pollutant distribution and trends.  
3. Develop predictive models using XGBoost and tune model parameters to obtain the best model.    
4. Use real-time data to predict future air quality.  

## Data Source
- Data is provided by Ambee based on a single latitude and longitude location.  
- Data includes pollutant concentrations, meteorological conditions (e.g., temperature, humidity, wind speed, precipitation), and other relevant indicators.  

## Project Structure
- data
  - [air.csv](air.csv)
  - [weather.csv](weather.csv)
- doc
  - [README.md](README.md)
- code
  - [Data collection.ipynb](Datacollection.ipynb)
  - [Real time Prediction.ipynb](RealtimePrediction.ipynb)

## Instructions
### Environment Setup
Ensure your system has the following:

- Python 3.9 or higher
- ArcGIS Online or ArcGIS API for Python
- Power BI

### Technology Stack
- Programming Language: Python  
- Data Processing: Pandas, NumPy  
- Visualization: ArcGIS, Power BI  
- Machine Learning Models: XGBoost  
- Data API: Ambee REST API 

## Contact
For questions or suggestions, contact Hanbin Zhang

Email: zhang.hanb0830@gmail.com  
Phone: +1 413-346-7903
