# Flight Delay Prediction

## Overview
This repository contains a machine learning project focused on predicting flight delays based on various features, including weather conditions, flight schedules, and federal holidays.

## Description
We aim to improve the customer experience for travelers by predicting flight delays. This project uses data from domestic flights operated by large US air carriers from 2014 to 2018. By integrating weather data and other relevant features, the model seeks to provide accurate delay predictions.

## Features

1. **Flight Data:** Contains flight details such as date, time, origin, destination, airline, distance, delay status, and more.
2. **Weather Data:** Provides weather conditions, including average temperature, wind speed, precipitation, snowfall, and snow depth.
3. **Federal Holidays:** An indicator variable to highlight if a flight date coincides with a federal holiday.

## Installation

```
git clone [https://github.com/eliasedwin7/DTS_Final_Flights.git](https://github.com/eliasedwin7/DTS_Final_Flights.git)
pip install -r requirements.txt
```

## Usage

1. Data Preprocessing:
   - Run the data cleaning and preprocessing section to handle missing values and create relevant features.
   
2. Model Training:
   - Use the provided Jupyter notebooks to train the machine learning model.
   
3. Evaluation:
   - Assess the model's performance using metrics like accuracy, precision, recall, and the ROC curve.
