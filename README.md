**Cropland Classification using Landsat 8 Imagery**

**Project Overview**

This project utilizes Google Earth Engine to classify cropland using Landsat 8 imagery. It predicts cultivated areas within specific geographical scopes between South Dakota and Minnesota for training, and North Dakota and Minnesota for testing. The application features a split-panel interface to compare actual labels with predictions and automatically zooms into a specific area of interest.

Features

UI Map: Displays predictions and actual data side-by-side in a split-panel view, focusing on a predefined area by automatically zooming to longitude -99.6664 and latitude 46.7718 with a zoom level of 14.
Landsat 8 Data: Uses imagery to predict land cultivation.
Classification Model: Employs a random forest classifier trained on selected data points.
Technology Stack

Visit the live application here: https://ee-ashnagupta.projects.earthengine.app/view/cultivate-land-prediction
Cultivated Land Prediction App. This link will take you to the deployed application where you can view the interactive results and explore the map layers.



The model achieves approximately 73% accuracy in predicting cultivated lands, providing valuable insights into crop type distribution in the tested regions.
