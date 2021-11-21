# Adding geospatial context to a dataset
## Data analysis of the Airbnb dataset of Seattle.
This a short analysis to illustrate if adding the distance to an art galley, museum or other cultural center help improve a model to predict the price you pay per night for your Airbnb. The Airbnb dataset used for this exercise was downloaded from the website [Inside Airbnb](http://insideairbnb.com/) and the inventory of cultural sites was downloaded from [Seattle's Open Data Portal](https://data.seattle.gov/). Using these publicly accessible datasets we will show how to give some spatial context to a dataset while trying to answer the following questions:

1. Are the neighborhoods with most expensive Airbnb prices per night the ones with the shortest average distance to cultural sites?
2. Does the variable 'distance' help create a more accurate predictive model?
3. Which are the most important variables for predicting price per night?

## Requirements
This is the list of Python libraries used:
* Numpy
* Pandas
* Geopandas
* Scikit-Learn

## Results
The inclusion of a geospatial variable called 'distance', which stands for the closest distance in meters from an Airbnb unit to a cultural site (e.g. art gallery, concert hall), slightly improved the model accuracy. This results can be used to increase awareness of the importance of geospatial variables in some modeling scenarios.