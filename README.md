# Adding geospatial context to a dataset
## Data analysis of the Airbnb dataset of Seattle.
This a short analysis to illustrate if the distance to an art galley, museum or other cultural center might influence the price you pay per night for your Airbnb. The Airbnb dataset used for this exercise was downloaded from the website [Inside Airbnb](http://insideairbnb.com/) and the inventory of cultural sites was downloaded from [Seattle's Open Data Portal](https://data.seattle.gov/). Using these publicly accessible datasets we will show how to give some spatial context to a dataset while trying to answer the following questions:

1. Which are the most expensive neighborhoods in Seattle and what is their average distance to cultural sites?
2. Is there a correlation between price per night and the proximity to city's cultural sites?
3. Which are the most influential variables for predicting price per night?

## Requirements
This is the list of Python libraries used:
* Numpy
* Pandas
* Geopandas
* Scikit-Learn

## Results
The inclusion of a geospatial variable called 'distance', which stands for the closest distance in meters from an Airbnb unit to a cultural site (e.g. art gallery, concert hall), could be considered for more complex price modeling given its importance is not negligible in the linear model created in this exercise.