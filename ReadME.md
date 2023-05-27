# Analysis of Crime Data in Toronto
This repository contains an analysis of crime data in Toronto, focusing on patterns of crime and potential factors influencing crime locations. The analysis involves accessing the crime dataset from the Toronto Public Service Public Safety Data Portal and utilizing spatial analysis techniques.

## Part A: Cluster Analysis

* Density Map
The crime dataset is analyzed to determine if crimes are clustered. A density map is created using the quadrat or kernel method to visualize the local density of crimes. The density map provides insights into areas with high crime concentration and areas with lower crime rates.

* Spatial Outliers and Trends
The selected crime data is examined to identify spatial outliers or trends. Statistical tests and visualizations are employed to detect any unusual patterns or spatial trends in the distribution of crimes. Maps and figures are generated to visualize the results and support the analysis.


## Part B Probability of Spatial Pattern

* Moran's I
The spatial pattern of crimes is assessed using Moran's I, a measure of spatial autocorrelation. Moran's I evaluates whether the observed crime pattern is clustered, dispersed, or randomly distributed. Graphs and text are used to present the results and support the analysis.
    

* Factors Influencing Crime Location
Apart from the crime data, other datasets from the City of Toronto or other providers are explored to identify potential factors influencing the location of crimes. Factors such as age, employment, income, or demographic information might be considered. Plots, graphs, and statistical analysis are used to investigate the relationships between these factors and crime locations.
The analysis aims to provide insights into the spatial patterns of crimes in Toronto and explore potential contributing factors. The code, data, visualizations, and findings are presented in the notebook to facilitate a comprehensive understanding of the analysis process and results.


## Aknowlegement
The analysis and methodology in this repository draw inspiration from the following sources:
[Rey, S. J., & Anselin, L. (2021). Point pattern analysis. Geographic Data Science, Chapter 8]-https://geographicdata.science/book/notebooks/08_point_pattern_analysis.html
[Darribas, I. (n.d.). Geovisualization with PySAL. Geographic Data Science, Lab 8.]-https://darribas.org/gds_course/content/bH/lab_H.html
[PySAL Developers. (n.d.). Moran’s I visualization. PySAL]-https://pysal.org/notebooks/viz/splot/esda_morans_viz.html
[City of Toronto. (2016). Neighbourhood profiles. Open Data Catalogue]-https://open.toronto.ca/dataset/neighbourhood-profiles/
[ArcGIS Hub. (n.d.). Toronto neighbourhoods. ArcGIS Online]-https://edu.hub.arcgis.com/datasets/edu::toronto-neighbourhoods-1/explore?location=43.717982%2C-79.377254%2C11.64
[City of Toronto. (n.d.). Catalogue. Open Data Catalogue]-https://open.toronto.ca/catalogue/
[Toronto Police Service Open Data Portal. (n.d.)]-https://data.torontopolice.on.ca/

