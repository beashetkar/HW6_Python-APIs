
# WeatherPy

Date : 12/23/2017

Whether financial, political, or social -- data's true power lies in its ability to answer questions definitively. 

The Analysis consists in visualizing the weather of randomly selected 500+ cities across the world of varying distance from the equator and creating a representative model of weather across world cities.

The goal is to build a series of scatter plots to showcase the following relationships:

Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude

The  HW_WeatherPy.ipbn notebook includes:

### the following dependencies: 
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import requests as req
import time
from datetime import datetime

import openweathermapy.core as ow
from citipy import citipy

### Call the following functions: 

1) coordinates_func():
2) first_upper(s):
3) get_file_contents(filename):
4) convert_date(day):
5) set_plot_labels(x_title, y_title, day, x_limit , y_limit, savefig):

### Perform API Calls

Perform a weather check on each of the cities using a series of successive API calls.

## PLOTTING THE RESULTS

### Latitude vs Temperature Plot

Show the figure

![png](HW_WeatherPy_files/HW_WeatherPy_22_0.png)


#### Conclusions:

The temperature along Latitude chart clearly represents that the cities close by or in the zone between the tropics of capricorn and cancer (-23.5 , 23.5) , including the equator line, have the higher temperatures. So, It is possible to come a conclusion that temperature gets hotter as it approaches the equator.

### Longitude vs Temperature Plot


![png](HW_WeatherPy_files/HW_WeatherPy_25_0.png)


### Humidity (%) vs. Latitude

![png](HW_WeatherPy_files/HW_WeatherPy_27_1.png)

### Conclusions:

The Humidity along Latitude chart shows that humidity of a city is not related to the latitude at all. We can find cities with different latitudes with high percentage of humidity.

### Cloudiness (%) vs. Latitude

![png](HW_WeatherPy_files/HW_WeatherPy_30_0.png)

### Wind Speed (mph) vs. Latitude

![png](HW_WeatherPy_files/HW_WeatherPy_32_0.png)

### Conclusions:

The Win speed along Latitude chart shows that the win speed is not too related to the latitude. Most of our sample cities have low wind speed. 
