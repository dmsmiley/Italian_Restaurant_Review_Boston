# Italian Restaurant Reviews in Boston

This project will list and visualize the amazing Italian restaurants in the city of Boston.

![Antico Forno](aubrey-odom-ngIvPcopNpE-unsplash.jpg)

<span>Photo by <a href="https://unsplash.com/@octoberroses?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Aubrey Odom</a> on <a href="https://unsplash.com/?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span>

___
### Data
- Boston neighborhood latitude and longitude information comes from a csv file which was compiled by googling the individual areas.
- Italian restaurant in each neighborhood comes from FourSquare API
- GeoJSON data for Folium map comes from Boston Open Data.

___
### Approach
- By collecting the data from Boston Open Data and using FourSquare API we will find all venues for each neighborhood.
- Filter out all venues that are Italian restaurants.
- Find ratings, tips, and like count for each Italian restaurant using FourSquare API.
- Using rating for each restaurant, we will sort the data.
- Visualizing the rankings of each neighborhood using Folium.

___
### Questions
- What area has the most Italian restaurants in Boston?
- Which areas lack Italian restaurants?
- Which areas would be best to visit if you want quality Italian cuisine?

___
### Import Libraries for Analysis
- Pandas and Numpy for handling the data
- Request for using FourSquare API
- Geopy to get coordinates of Boston
- Folium to visualize the maps
