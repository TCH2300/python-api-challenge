# python-api-challenge

## Part I: WeatherPy

Please Note: To successfully run the code in Part I, an API key must be obtained from openweathermap.org/api. 

In this part of the assignment, a Python script was created to visualize the weather of 550+ cities across the world of varying distance from the equator. This was accomplished using Citipy (https://pypi.python.org/pypi/citipy and the Open WeatherMap API (https://openweathermap.org/api. 

Within the Python script, a series of scatter plots was created to showcase the following relationships:
* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

In addition to the above plots, a linear regression was ran for each relatonship above, further broken out by Northern and Southern Hemisphere.

A written analysis for each plot is included within the Jupyter Notebook. The csv of the cities and png versions of all plots are included in the output_data folder. The Jupyper Notebook to review the code is saved as: WeatherPy_main.ipynb 

## Part II: VacationPy

Please Note: To successfully run the code in Part II, a Google Places API key must be obtained.  

In this part of the assignment, the city data generated from Part I as a csv file was brought in for further analysis. The analysis utilized jupter-gmaps and the Google Places API. In this part of the assignment, a Heat Map was created to display the humidity for every city from Part I. A screen shot of the heatmap is included in the VacationPy folder. The code for this portion of the assignment is saved in the Jupter Notebook file: VacationPy_main.ipynb

Please Note: The cities_copy.csv is the csv of cities used in Part I, however, it does not match the final output that was used for Part I. It still gets to the point of the exercise, but Part I had to be re-run after the heat map for Part II had been completed, so the csv file for Part II was not updated to match Part I. 

Additionally, the portion of Part II pertaining to ideal weather conditions and hotel plotting was not completed by the assignment deadline due to time constraints. 


