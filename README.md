# dublin_bikes
Clustering and Forecasting-driven analysis of Dublin Bikes public data to examine movement patterns and behaviours

This Git contains the workflow used for an analysis of the Dublin Bikes station occupancy data publicly available on the Smart Dublin Open Data Store https://data.smartdublin.ie/dataset/dublinbikes-api. The files used were:
- dublinbikes_20190401_20190701.csv
- dublinbikes_20190701_20191001.csv
- dublinbikes_20191001_20200101.csv
- dublinbikes_20200101_20200401.csv

The weather data comes from the Irish Meteorological Society website https://www.met.ie/climate/available-data/historical-data. The file used is included in the repository (hly175.csv).

The Jupyter notebook uses common libraries to perform visualization (charts & map-based), K-Means Clustering and a Random Forest Classifier. 

Known issues: While the code works fine, there are plenty of simplifications that could be made and unpythonic language.
