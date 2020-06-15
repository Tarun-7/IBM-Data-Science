# Project

This Project involves Clustering Neighborhoods of London to identify suitable locations to open an Asian cusine in London.

### Data:
1. Neighborhoods data of London is Webscraped from ['List of areas of London, Wikipedia page'](https://en.wikipedia.org/wiki/List_of_areas_of_London)
2. Demographic information of London is scrapped from ['Demography of London, Wikipedia page'](https://en.wikipedia.org/wiki/Demography_of_London)
3. Geopy library of python is used to get the location coordinates of each Neighborhood.
4. Foursqaure API is used to identify venues in each neighborhood.

### Methodology:
- Using the extracted neighborhoods data and demographics data, the top-8 London neighborhoods with most asian population are Identified.
- Co-ordinates(latitudes and Longitudes) are added to each neighborhood using Geopy library.
- Top-100 venues are explored for each neighborhood using Foursquare API.
- A final dataframe is created with neighborhoods and their top-10 most frequent venues.
- Using K-Means Clustering, the neighborhoods are Clustered. (Elbow method is used to identify appropriate number of clusters.)
- Folium library is used to visualize the clusters.

### Results:
! [Result](https://github.com/Tarun-7/IBM-Data-Science/blob/master/Applied%20Data%20Science%20Capstone/Week%20-5/Results.PNG)
             

### Author
Tarun Sunkara | [LinkedIn](https://www.linkedin.com/in/tarunkumar-sunkara/)
