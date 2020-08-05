# Airbnb (Amsterdam) Data

## Data

The data can be found [here](http://insideairbnb.com/get-the-data.html). We will be using these data files: 

- *detailed_listings:* Detailed listings for Amsterdam. 
- *calenar:* Detailed calendar data for listings in Amsterdam.
- *listings:* Summarized listings information for Amsterdam.

Process can be found [here.](https://github.com/ZippySphinx/Airbnb-Data/blob/master/Airbnb_Data.ipynb)


## Summary
- The peak in prices occur in the period between May and June and the cheapest period is between april and feb.
- The Most Expansive neighbourhood is Centrum-West followed by Centrum-Oost which is reasonable since it is the city center while the cheapest listings are in Bijlmer-Centrum and Bijlmer-Oost which is part of Amsterdam Southeast.
- The prices in the center is about double the prices in the southeast and westernmost neighbourhoods.
- The price to the availability of listings to produce the curve which shows the inverse relation between the availability and the average price.
- Attributes associated with the price of a listing
  - Property type
  - Neighbourhood
  - Reviews in terms of review count and the recency of the reviews
  - Room Type
  - Host Acceptance Rate

### Packages Used
- scikit-learn
- pandas
- Python
- numpy
- matplotlib
- seaborn