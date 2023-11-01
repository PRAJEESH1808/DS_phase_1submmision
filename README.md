# DS_phase_1submission
Phase 1submission
# Electricity Price Prediction Dataset

This repository contains a dataset and associated resources for electricity price prediction. The dataset is intended for use in machine learning and data analysis projects to predict electricity prices. This README file provides an overview of the dataset, its contents, and how to use it.

## Dataset Description

### About the Dataset

The dataset contains historical data on electricity prices, weather conditions, and other relevant features that can be used for predicting electricity prices. The data is collected from various sources and has been preprocessed for ease of use in machine learning projects.

### Data Columns

The dataset includes the following columns:

- `DateTime`: Date and time of the data point.
- `ForecastWindProduction`: wind produced by the year
- `ORKTemperature`: The temperature during the same time period.
- `humidity`: Humidity during the same time period.
- `ORKWindspeed`: Wind speed during the same time period.
- `solar_radiation`: Solar radiation during the same time period.
- `precipitation`: Precipitation during the same time period.
- `day_of_week`: The day of the week (0-6, where 0 is Monday and 6 is Sunday).
- `hour_of_day`: The hour of the day (0-23).

### Data Sources

The dataset combines data from various sources, including weather data, electricity price data, and other relevant sources. All data sources are cited in the dataset, and references are provided for further exploration.

## Usage

### Data Preprocessing

Before using the dataset for machine learning, you may need to preprocess the data. Depending on your specific use case, you may want to handle missing values, normalize or scale features, and split the data into training and testing sets. We recommend using Python and popular libraries like Pandas and Scikit-Learn for data preprocessing and machine learning tasks.


# Data Source:
 
 Dataset Link: (https://www.kaggle.com/datasets/chakradharmattapalli/electricity-price-prediction)



### Example Usage

Here is a simple example of how to load the dataset using Python and Pandas:

```python
import pandas as pd

# Load the dataset
data = pd.read_csv('electricity_price_prediction_dataset.csv')

# Explore the data
print(data.head())
```
