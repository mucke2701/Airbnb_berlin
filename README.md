# Airbnb_berlin
**Data Science Project on Airbnb Listings**

Check also my Story on Medium: https://medium.com/@mauricio.leao.hess/all-you-need-to-know-in-data-science-with-airbnb-berlin-listings-586a40d37c1e

**Motivation**

In this project we used descriptive statistic to analyze the airbnb listing dataset of berlin from 22.09.2021, handled different types of data (e.g. missing data, outliers and categorical), predicted the prices of listings with KNN-Regression and Ridge-Regression and did a basic visualization of geo-data with geopandas of the most reviewed listings in berlin. This project can be used as an exercise for a beginning data scientist.

**Summary**

The prediction of the Ridge-regression model is slightly better than the KNN-regression model. I used as measurement of the prediction the coefficient of coordination.

The visualizations show us the average prices and sum of the prices per district. The plots shows us clear differences at the prices and numbers of listings for the districts. 

Also I did a basic Geo-visualization with Geo-Panda to show the most reviewed listings. It shows that the most reviewed listings are all central located.

Files in this project:
- listings.csv -> csv-File of Berlin Airbnb-Listing 
- bezirksgrenzen.dbf -> dbf-file for Berlin geomap
- bezirksgrenzen.shp -> shp-file for Berlin geomap
- bezirksgrenzen.prj -> prj-file for Berlin geomap
- bezirksgrenzen.shx -> shx-file for Berlin geomap
- bezirksgrenzen.xsd -> xsd-file for Berlin geomap
- Airbnb.ipynb -> Jupyter Notebook with all the code and visualization

Libraries needed in this project:
- pandas 
- numpy
- matplotlib.pyplot
- sklearn.preprocessing
- seaborn
- sklearn import neighbors
- sklearn import linear_model
- sklearn.model_selection import train_test_split
- sklearn.metrics import r2_score, mean_squared_error
- sklearn.decomposition import PCA
- geopandas
- shapely.geometry import Point, Polygon
- descartes

**Necessary acknowledgments**

Thanks to Udacity
