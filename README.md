# Blog Post

Check out the blog post below!

[Inspecting the Seattle Airbnb Open Dataset](https://medium.com/@av.mol.th/inspecting-the-seattle-airbnb-open-dataset-b999d7e5cca7)

# Dataset
Seatle Airbnb Open Data
https://www.kaggle.com/datasets/airbnb/seattle?resource=download

# Buisness Understanding 
Airbnb (ABNB) is an online marketplace that connects people who want to rent out their homes with people who are looking for accommodations in specific locales.

# Data files
The following Airbnb activity is included in this Seattle dataset:

    Listings, including full descriptions and average review score
    Reviews, including unique id for each reviewer and detailed comments
    Calendar, including listing id and the price and availability for that day

# Libraries
- [pandas](https://pandas.pydata.org/)
- [matplotlib](https://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/)

# Questions

## Q1) Which neighbourhoods have the highest price in Seattle?

From the boxplot we can see that on average Magnolia has the highest priced listings whereas Delridge has the lowest priced listings. We can also see that Magonlia has the highest variation in prices across the listings. We've chosen a boxplot for showing the data so we can get a broader understanding of the data. We could have just extracted the highest mean value, however this would not give us information about the variability in the data.

## Q2) Does the number of ammenities offered correlate with the price of the listing? and does the Magnolia neighbourhood offer more ammenities?

It doesn't look like there is a correlation between the price and the number of amenities. That's great news for AirBnB customers as they have alot of choice at lower proce points that contain a large number of amenities. AirBnB hosts don't have to worry about adding more amenities to get higher price points. The investment into more amenities may not pay off, and there are cheaper apartments available.

## Q3) In which month are the listings in the magnolia neighbourhood priced the highest?

We see there is not much seasonal fluctuation. The mean price is almost constant and there appears to be a slight spike in price in July 2016 and January 2017.

# Jupyter Notebook

The [Jupyter Notebook](data_analysis.ipynb) with the executed code is in `data_analysis.ipynb`

