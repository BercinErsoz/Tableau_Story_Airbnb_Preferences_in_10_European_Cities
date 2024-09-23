# Create a Tableau Story Airbnb Data


[Final: Tableau Story from Airbnb Data]([https://public.tableau.com/views/AirbnbPreferencesin10EuropeanCities/Story1?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link](https://public.tableau.com/views/AirbnbPreferencesin10EuropeanCities/map?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link))


## Summary
I examined some price drivers (location, quality, reviews etc.) of Airbnb listings with open data and create a story via Tableau Public for 10 European Cities.

## Design
* I looked at how each factor(hosting status, weekend/weekday status, cleanliness rating, guest satisfaction rating, 4 location indicators) affect price.



## Facts
* By using cross-sectional Airbnb data for European cities, some price drivers (location, reviews, quality etc.) are examined. Although Amsterdam takes the lead in the most expensive cities, Athens seems to be the most affordable city on the  average. When the you click on the Cities, weekday and weekend prices are also shown in detail.
    * tool: mapping, adding second graph via Tooltip, adding third graph via Tooltip, filtering accoring to City
 
* Specified characteristics of listings, including the high values of guest satisfaction and  cleanliness ratings of customers are common for Airbnb listing system as expected. Most of the accommodation is single bedroom (70%). Most of the listings in Athens, Budapest, Paris, Vienna and Amsterdam are entire homes, while more than 50% of the listings in Barcelona, Berlin and London are private rooms.
    * tool: adding dashboard to a story, barcharts, piecharts

* Average prices are seem to be below their relative medians in all of these Cities and their standard deviations could be said as high. These statistics show skewed price distributions with a long tail towards higher values. As expected, weekends are more expensive than weekdays (1-11%) except Athens and Paris.
    * tool: boxplots, sizing according to price, filtering cities

* Average prices in terms of professional hosting status in the Cities may suggest that professional hosts  provide accommodation at higher level except from Amsterdam, Budapest and London.  Another determinant for professionalism could be multiple listings by hosts. Filtering according to city reveals that  hosts with multi offerings charge higher prices than hosts with single offer, especially hosts with more than four listings (business hosts). Regulatory differences among these European Cities may be the reason for this in  the structure of Airbnb networks. In general, professional hosts constitute  majority of listings among the Cities.
    * tool: polygon, sizing according to hosting status, filtering cities, adding average price as label

* Location is a key factor in the accommodation: distance from the city centre,  proximity to attractive points & proximity to restaurants and access to nearest metro. Indexes for attractiveness of neighbourhoods and restaurants are based on TripAdvisor data. There seems to be there are no significant relationships in expected directions (negative with dist_city_center, metro_dist; positive with att_index, rest_index)  for between them. Further analyses are required for conclusive results.
    * tool: density graphs, adding trend lines

* When the prices are analyzed with the same four location variables, it is considered that attractiveness of the neighborhood is the variable that can be the most effective in most of the Cities. In addition, as expected, distance to the city center and metro is inversely related to price, while attractiveness and restaurant indices are related positively.  In the City detail, attribution index seems to affect the price more in Amsterdam, London and Paris according to the slope of the trend line. As mentioned before, further analyses are required for conclusive results.
    * tool: adding dashboard to a story, density graphs, adding trend lines, filtering cities

## Resources
[Open Data](https://doi.org/10.1016/j.tourman.2021.104319)


## Data Files
[Kaggle](https://www.kaggle.com/datasets/thedevastator/airbnb-price-determinants-in-europe)
