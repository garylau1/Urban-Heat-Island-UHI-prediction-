# Urban-Heat-Island-UHI-prediction-
In this project, we developed a sophisticated machine learning regression model to identify and predict Urban Heat Island (UHI) hotspots in New York City. A key technical achievement of this work was the successful integration of <b>four distinct datasets</b>: 
- ground-level traverse temperature readings (Landsat_LST.tiff20%)
- multi-spectral satellite imagery (Sentinel-2 Data.csv)
- real-time meteorological data(NY_Mesonet_Weather.xlsx)
- urban building footprints(Building_Footprint.kml)
-  We utilized advanced <b>GeoPandas</b> techniques to perform complex spatial joins and temporal merging, creating a unified geospatial dataset that correlates physical urban morphology with environmental conditions. By training a Random Forest Regressor on this rich feature set, we were able to accurately predict the UHI Index (around 90% accuracy), demonstrating comprehensive proficiency in geospatial data engineering, feature extraction, and predictive modeling for environmental analysis.

PS: our work is improved based on EY Data Challenge
