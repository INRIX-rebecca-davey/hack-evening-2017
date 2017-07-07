# INRIX Hack Evening 2017

## About

Words here

## Schedule

Words here

## The data

In the 'data' directory you'll find the data we'll be looking at tonight. It describes all road traffic accidents in Leeds from 2009 to 2015 that involve at least a minor injury. As you'll see, there are many interesting features to work with, including road surface conditions, lighting conditions, number of vehicles involved etc. 

We've provided the raw files of the separate years, and additionally the following files:

* all.csv - all raw year files together
* cleaned.csv - several data cleaning steps applied to all.csv, described in 'cleaning-steps.txt'
* cleaned-with-latlng.csv - cleaned.csv but with latitude and longitude values instead of easting and northing - much easier to work with!

Link to data on data.gov.uk site: https://data.gov.uk/dataset/road-traffic-accidents

We chose this dataset for a few reasons
* it's relevant to our own work! We love traffic data.
* it's nearly local, just a short hop across the Penines away
* it has so many features! Great for machine learning, and rich for visualisation and mapping

## Suggested challenges

Below we've described some suggested challenges (two for machine learning and three for visualization).
If you have an idea for something you'd rather work on, that's great! Run it by one of our team and 
we can help you hash out a plan and get started.

### Challenge 1: machine learning - prediction

Description: use data features (existing or engineered) to develop a model that can predict casualty severity

Suggested tools: scikit-learn (Python), TensorFlow, Caret (R)

Example of similar work:

### Challenge 2: machine learning - time series

Description:

Suggested tools:

Example of similar work:

### Challenge 3: visualization - mapping

Description: an interactive map, with filters, e.g. markers for accidents but only show those with at least 3 vehicles involved, or choose feature to enhance map (e.g. colour roads by severity)

Suggested tools: Folium (Python), Leaflet (JS), Mapbox (JS), QGIS

Example of similar work:

### Challenge 4: visualization - dashboard

Description:

Suggested tools: Dash (Python), Tableau

Example of similar work:

### Challenge 5: visualization - infographic

Description:  a static or responsive infographic exploring the dataset

Suggested tools: Tableau

Example of similar work:

