# 🚴 London Bike Sharing Data Analysis

*Data Analytics Project Using Python (Jupyter Notebook) and Tableau*

##📌 Overview

This project analyzes London **Bike Sharing data** from Kaggle, containing **17,414** bike rental records. The goal is to understand how weather conditions, temperature, wind speed, seasons, and time affect bike-sharing usage in London. These insights can help improve operational planning, optimize bike availability, and enhance urban transportation strategies.

## 📊 Dataset Summary

**Total Rows:** 17,414

**Total Columns:** 10

### **Key Feature Categories**

**Timestamp:** Date and time of bike rentals
**Count:** Total number of bikes rented at that timestamp
**Temperature:** t1 – recorded temperature, t2 – adjusted temperature
**Weather & Environment:** Humidity (hum), Wind Speed (wind_speed), Weather Code (weather_code)
**Season:** Season of the year (1 = spring, 2 = summer, 3 = fall, 4 = winter)

## 🐍 Exploratory Data Analysis (Python)

### ✔️ Data Loading & Cleaning

- Imported dataset using **pandas**
- Inspected structure using .head() and .info()
- Renamed columns for clarity
- Converted humidity from 0–100 scale to 0–1 scale
- Standardized data types for season and weather_code

### ✔️ Feature Labeling & Mapping

- Mapped numeric codes to meaningful labels
- Improved interpretability for analysis and visualization

### ✔️ Exporting Cleaned Data

Cleaned dataset saved as london_bikes_final.csv for further analysis and visualization

## 🧠 Data Analysis Insights

- Python-based analysis included:
- Trend analysis of bike rentals over time
- Impact of weather conditions on bike usage
- Seasonal and temporal patterns of bike-sharing demand
- Correlation between temperature, wind speed, humidity, and rental counts

## 📈 Tableau Dashboard

- An interactive Tableau dashboard was created to visualize:
- Bike rental trends over time
- Impact of weather and seasons on usage
- Hourly and daily rental patterns
- Impact of wind speed and temperature on usage

## 🛠 Technologies Used

- Python: pandas
- Jupyter Notebook for data cleaning and analysis
- Tableau for interactive dashboard creation
