# Airbnb_berlin
Data Science Project on Airbnb Listings

In this project we used descriptive statistic to analyze the airbnb listing dataset of berlin from 22.09.2021, handled different types of data (e.g. missing data, outliers and categorical), predicted the prices of listings with KNN-Regression and Ridge-Regression and did a basic visualization of geo-data with geopandas of the most reviewed listings in berlin. 

Files in this project
listings.csv -> csv-File of Berlin Airbnb-Listing
bezirksgrenzen.dbf -> dbf-file for Berlin geomap
bezirksgrenzen.shp -> shp-file for Berlin geomap
bezirksgrenzen.prj -> prj-file for Berlin geomap
bezirksgrenzen.shx -> shx-file for Berlin geomap
bezirksgrenzen.xsd -> xsd-file for Berlin geomap
Airbnb.ipynb -> Jupyter Notebook with all the code and visualization

Libraries needed in this project:
pandas
numpy
matplotlib.pyplot
sklearn.preprocessing
seaborn
sklearn import neighbors
sklearn import linear_model
sklearn.model_selection import train_test_split
sklearn.metrics import r2_score, mean_squared_error
sklearn.decomposition import PCA
geopandas
shapely.geometry import Point, Polygon
descartes


