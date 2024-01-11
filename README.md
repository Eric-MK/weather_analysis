# Weather Data Analysis

### This project performs Weather data analysis using Python with [pandas](https://pandas.pydata.org/) library.


#### Comprises a Data_test directory with a CSV file as the data set encompassing weather data for 12 months.

#### Table Format
======
Date/Time       | Temp_C           | Dew Point Temp_C  | Rel Hum_%  | Wind Speed_km/h  | Visibility_km | Press_kPa | Weather |
| ------------- |:-------------:| -----:|-----:|-----:|-----:|-----:|-----:|
| 1/1/2012 0:00   | -1.8	 | -3.9 | 86|4|8|101.24|Fog|
| 1/1/2012 2:00      | -1.8|  -3.4 |89|7|4|101.26|Freezing Drizzle,Fog|

### Tools
- Jupiter Notebook [Download here](https://jupyter.org/install)

###  Practices done
- Find all the unique 'Wind Speed' values in the data
- Find the number of times when the Weather is exactly Clear
- Find the number of times when the 'Wind Speed was exactly 4 km/h
- Find the mean Visibility
- Find the Standard Deviation of Pressure
- Find the variance of Relative Humidity
- Find all instances when Snow was recorded
- Find all instances when Wind Speed is above 24 and Visibility is 25
- Find the Mean value of each column against each Weather Condition
- Find the Minimum and Maximum value of each column against the weather condition
- Find all instances when the Weather is clear or Visibility is above 40
- Find records where the weather is clear and Relative Humidity is greater than 50 or Visibility is above 40
### Data Cleaning and Preparation
1. Clean the data by checking for missing values represented as NaN (Not a Number)
