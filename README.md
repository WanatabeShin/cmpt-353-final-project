# CMPT 318 Final Project

## Installing

Before running any of the jupyter notebooks, you need to install some requirements

Python 2

```
pip install -r requirements.txt
```

Python 3

```
pip3 install -r requirements.txt
```

## Running Order

In the root directory run:

```
jupyter-notebook
```

## 1. Cleaning the Data

First we need to clean all of our original data

* `clean_data.ipynb:` Used to clean the Vancouver Crime dataset
* ` weather/weather_data_processing.ipyn:` Used to clean the Vancouver Weather dataset

## 2. Running the Analysis

After cleaning is done, any of these files can be ran

* `trend.ipynb` 
* `classifier.ipynb` 
* `days_comparison.ipynb` 
* `weather/weatherAnalysis.ipynb` 

## Project Structure

```
.
├── README.md
├── classifier.ipynb
├── clean_data.ipynb
├── dataset
│   ├── bike_lane.csv
│   ├── clean_bike_data.csv
│   ├── cleanedWeatherData.csv
│   ├── crimedata_csv_all_years.csv
│   └── raw_bike_data.csv
├── days_comparison.ipynb
├── images
│   ├── Crime\ and\ Weather\ Distribution1.png
│   ├── Crime\ and\ Weather\ Distribution2.png
│   ├── bike_theft_probability_neighbourhood.png
│   ├── heatmap.png
│   ├── hourly_bicycle_theft.png
│   ├── monthly_bike_theft_2003_2010.png
│   ├── monthly_bike_theft_2003_2019.png
│   ├── monthly_bike_theft_2011_2019.png
│   ├── yearly_days_comparison.png
│   ├── yearly_linear_regression.png
│   └── yearly_weekdays_comparison.png
├── models
│   ├── DecisionTreeClassifier.joblib
│   ├── GaussianNB.joblib
│   ├── GradientBoostingClassifier.joblib
│   └── RandomForestClassifier.joblib
├── requirements.txt
├── trend.ipynb
└── weather
    ├── clean_bike_data.csv
    ├── cleanedWeatherData.csv
    ├── daily_2014_2019
    │   ├── en_climate_daily_BC_1108395_2014_P1D.csv
    │   ├── en_climate_daily_BC_1108395_2015_P1D.csv
    │   ├── en_climate_daily_BC_1108395_2016_P1D.csv
    │   ├── en_climate_daily_BC_1108395_2017_P1D.csv
    │   ├── en_climate_daily_BC_1108395_2018_P1D.csv
    │   └── en_climate_daily_BC_1108395_2019_P1D.csv
    ├── dataURLList.txt
    ├── hourly_2016_2018
    │   ├── 2016
    │   ├── 2017
    │   ├── 2018
    │   └── 2019
    ├── weatherAnalysis.ipynb
    └── weather_data_processing.ipynb
```

## Datasets

1. [Original Dataset for Vancouver Crimes from VPD OPEN DATA](https://geodash.vpd.ca/opendata/)

2. [Original Dataset for Vancouver Weather from Government of Canada](https://climate.weather.gc.ca/historical_data/search_historic_data_e.html)

## Final Report
The link below contains the report for the project
https://docs.google.com/document/d/1bUQy_Kf23t6kQHgW0GSFMD1jJs-9r0piMrDd9bQy0P4/edit?usp=sharing
