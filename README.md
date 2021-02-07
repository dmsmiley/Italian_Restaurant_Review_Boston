# Italian Restaurant Reviews in Boston
### Introduction
This project will seek to list and visualize the amazing Italian restaurants in the city of Boston.


### Data
- Boston neighborhood latitude and longitude information comes from a csv file which was compiled by googling the individual areas.
- Italian restaurant in each neighborhood comes from FourSquare API
- GeoJSON data for Folium map comes from Boston Open Data.

### Approach
- By collecting the data from Boston Open Data and using FourSquare API we will find all venues for each neighborhood.
- Filter out all venues that are Italian restaurants.
- Find ratings, tips, and like count for each Italian restaurant using FourSquare API.
- Using rating for each restaurant, we will sort the data.
- Visualizing the rankings of each neighborhood using Folium.

### Questions
- What area has the most Italian restaurants in Boston?
- Which areas lack Italian restaurants?
- Which areas would be best to visit if you want quality Italian cuisine?

### Import Libraries for Analysis
- Pandas and Numpy for handling the data
- Request for using FourSquare API
- Geopy to get coordinates of Boston
- Folium to visualize the maps
