# Accessing-OpenStreetMap-Data
A Jupyter project that demonstrates how to access local data from OpenStreetMap to improve your ML models. Demonstrates the use of K-D Trees to turn data into features.


This Jupyter Project demonstrates how to gather local amenity data from OpenStreetMap. Local amenity data of this sort could be used to improve the accuracy of a whole range of ML models. If, for example, you wanted to predict the price a AirBnb host might charge in parts of London, you might want to know something about the local amenities that exist within the area.

In this notebook we cover the following:

- How to make basic requests from OpenStreetMap using OSMnx
- Converting geographic projections.
- Using K-D Trees to to efficiently calculate the number of amenities that fall within a 5 minute walk of each AirBnb (approximately 0.5km distance).
