# Earthquake Prediction

As a group we are trying to come up with an solution to this question:

### What is the probability of an earthquake occurring in a chosen location in China and its surroundings?

Earthquakes are the sudden and violent shaking of the ground caused by the movement of tectonic plates which causes are amounts of devastation. We believe that predicting earthquake probability for a given coordinate can provide valuable information for disaster management and emergency response, and can ultimately help to save lives and reduce the impact of earthquakes on communities. Our objective is to use an earthquake dataset to find out the probability of an earthquake happening given a pair of coordinates using clustering.


## File desciption

earthquakePredictionProject.ipynb -> A Jupyter Notebook containing the main source code for the project.

earthquakedata.csv -> Dataset used for project

SC1015 Earthquake Prediction.pptx -> Presentation slides used for video presentation

Link to video presentation -> https://www.youtube.com/watch?v=JG0fVuyGdk0

## Team Members for C133 Team 4

Lee Min Han (U2222834A) 

Ravipudi Abhijeet Chowdary (U2220816C) 

Leong Ling Min Fernando (U2220587L)

## Models Used 

1. K-Means Clustering Model
2. Hierarchical Clustering Model

## Conclusion

- Heuristic approach to determine probability of earthquake has limitations 
- Closer to centroid of cluster, higher probability of earthquake
- In our case, K-Means Clustering model better than Hierarchical Clustering model in predicting earthquake after using average prediction error as a performance metric
- Proposed another solution which would be more accurate as it calculates the probability using the number of earthquakes in a radius around it divided by total number of earthquakes

## Things learnt from project

- How to do K-Means and Hierarchical Clustering
- How to determine optimal number of clusters using elbow method and dendrogram
- Splitting data into train and test set and using average prediction error to test the performance of clustering model
- Cartopy, geopy

## References

Dataset -> https://www.kaggle.com/datasets/jahaidulislam/significant-earthquake-dataset-1900-2023
https://www.askpython.com/python/examples/plot-k-means-clusters-python
https://scitools.org.uk/cartopy/docs/latest/reference/crs.html#
https://www.mapsofworld.com/lat_long/china-lat-long.html
https://towardsdatascience.com/plotting-geospatial-data-with-cartopy-4b5ad0da0761
https://www.datacamp.com/tutorial/k-means-clustering-python?utm_source=google&utm_medium=paid_search&utm_campaignid=19589720821&utm_adgroupid=143216588577&utm_device=c&utm_keyword=&utm_matchtype=&utm_network=g&utm_adpostion=&utm_creative=652967469592&utm_targetid=aud-299261629574:dsa-1947282172981&utm_loc_interest_ms=&utm_loc_physical_ms=9062546&utm_content=dsa~page~community-tuto&utm_campaign=230119_1-sea~dsa~tutorials_2-b2c_3-row-p1_4-prc_5-na_6-na_7-le_8-pdsh-go_9-na_10-na_11-na&gclid=Cj0KCQjw_r6hBhDdARIsAMIDhV-zcy01oetqnI9DO2lytzlSJPmvzITCzHZ6sR7JrT5WPHGUoHmd2eIaAkrwEALw_wcB
https://medium.com/@noahhradek/can-we-predict-earthquakes-using-pandas-cc3a55456969

