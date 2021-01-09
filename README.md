# 1. Introduction

The purpose of this project is to help people in exploring better facilities around their neighborhood. It will help people making smart and efficient decisions on selecting a great neighborhood out of the numbers of other neighborhoods in Scarborough, Toronto. Lots of people are migrating to various states of Canada and needed lots of research for good housing prices and reputed schools for their children. This project is for those people who are looking for better neighborhoods. For ease of accessing to Cafe, School, Supermarket, medical shops, grocery shops, mall, theatre, hospital, like-minded people, etc. This project aims to create an analysis of features for people migrating to Scarborough to search for the best neighborhood as a comparative analysis between neighborhoods. The features include median housing price and better school according to ratings, crime rates of that particular area, road connectivity, weather conditions, good management for an emergency, water resources both fresh and wastewater, and excrement conveyed in sewers and recreational facilities. It will help people to get the awareness of the area and neighborhood before moving to a new city, state, country, or place for their work or to start a new fresh life.

# 2. Data

Data Link: https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M

We will need data about different venues in different neighborhoods of that specific borough. In order to gain that information, we will use "Foursquare" locational information. Foursquare is a location data provider with information about all manner of venues and events within an area of interest. Such information includes venue names, locations, menus, and even photos. As such, the foursquare location platform will be used as the sole data source since all the stated required information can be obtained through the API. After finding the list of neighborhoods, we then connect to the Foursquare API to gather information about venues inside each and every neighborhood.

The data retrieved from Foursquare contained information of venues within a specified distance of the longitude and latitude of the postcodes. The information obtained per venue as follows:

1. Neighborhood
2. Neighborhood Latitude
3. Neighborhood Longitude
4. Venue
5. Name of the venue
6. Venue Latitude
7. Venue Longitude
8. Venue Category

# 3. Methodology

This project would use Four-square API as its prime data gathering source as it has a database of millions of places, especially their places API which provides the ability to perform location search, location sharing, and details about a business. Using credentials of Foursquare API features of near-by places of the neighborhoods would be mined. To compare the similarities of the two cities, we decided to explore neighborhoods, segment them, and group them into clusters to find similar neighborhoods in big cities. To be able to do that, we need to cluster data using the k-means clustering algorithm.

# 4. Result

## Map of Toronto
<img src = "brajeshmohapatra/coursera_capstone/Screenshot (133).png">


## Map of Scarborough

from IPython.display import Image
Image(filename = 'Screenshot (132).png')

# Discussion

The major purpose of this project, is to suggest a better neighborhood in a new city for the person who are shiffting there. Social presence in society in terms of like minded people. Connectivity to the airport, bus stand, city center, markets and other daily needs things nearby.

# Conclusion

In this project, using k-means cluster algorithm I separated the neighborhood into different clusters and for different lattitude and logitude from dataset, which have very-similar neighborhoods around them. I feel rewarded with the efforts and believe this course with all the topics covered is well worthy of appreciation. This project has shown me a practical application to resolve a real situation that has impacting personal and financial impact using Data Science tools. The mapping with Folium is a very powerful technique to consolidate information and make the analysis and decision better with confidence.
