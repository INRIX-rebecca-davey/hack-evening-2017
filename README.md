# INRIX Hack Evening 2017

## Schedule

18.00 - 18.20: welcome presentation

18.20 - 18.30: speed intros and forming teams

18.30 - 19.15: **first half**

19.15 - 19.30: grab some pizza!

19.30 - 20.30: **second half**

20.30 - 20.45: lightning presentations from teams

20.45 - 21.00: judging and prizes


## The data

In the 'data' directory you'll find the data we'll be looking at tonight. It describes all road traffic accidents in Leeds from 2009 to 2015 that involve at least a minor injury. As you'll see, there are many interesting features to work with, including road surface conditions, lighting conditions, number of vehicles involved etc. 

We've provided the raw files of the separate years, and additionally the following files:

* all.csv - all raw year files together
* cleaned-with-easting-northing.csv - several data cleaning steps applied to all.csv, described in 'cleaning-steps.txt'
* cleaned-with-latlng.csv - cleaned-with-easting-northing.csv but with latitude and longitude values instead of easting and northing - much easier to work with!

Link to data on data.gov.uk site: https://data.gov.uk/dataset/road-traffic-accidents

We chose this dataset for a few reasons:
* it's relevant to our own work! We love traffic data.
* it's nearly local, just a short hop across the Penines away
* it has so many features! Great for machine learning, and rich for visualisation and mapping

## Suggested challenges

Below we've described some suggested challenges (two for machine learning and three for visualization).
If you have an idea for something you'd rather work on, that's great! Run it by one of our team and 
we can help you hash out a plan and get started.

### Challenge 1: machine learning - binary prediction

Description: use data features (existing or engineered) to develop a model that can predict casualty severity (slight vs serious)

Example of similar work: [Overview of a ML approach to a binary classification problem](https://www.kaggle.com/c/titanic) and [for some ideas](https://www.quora.com/What-are-some-binary-classification-algorithms)

### Challenge 2: machine learning - time series modelling

Description: develop a time series model to fit and forecast the rate of accidents with time

Example of similar work: [A Time Series Model for Assessing the Trend and Forecasting the Road Traffic Accident Mortality](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5079210/)

### Challenge 3: visualization - mapping

Description: develop an interactive map, with filters, e.g. markers for accidents but only show those with at least 3 vehicles involved, or choose feature to enhance map (e.g. colour roads by severity)

Example of similar work: [Trafford Locality Assets](http://www.infotrafford.org.uk/assetmapping)

### Challenge 4: visualization - dashboard

Description: create an interactive dashboard exploring different ways of representing aspects of the dataset

Example of similar work: https://plot.ly/dash/gallery/new-york-oil-and-gas/

### Challenge 5: visualization - infographic

Description: create a static infographic representing aspects of the dataset that interest you 

Example of similar work: [Compilation of traffic accident infographics](http://graphs.net/infographics-on-accidents.html)

## Helpful tools

[Pandas](https://pandas.pydata.org/) - data handling & data analysis for Python

[Matplotlib](http://matplotlib.org/) - a Python library for 2D data plotting

[Seaborn](https://seaborn.pydata.org/) - a Python library for visualizing statistical data - based on maptlotlib

[Altair](https://altair-viz.github.io/) - a Python library for visualizing statistical data - pretty and easy to work with

[Bokeh](http://bokeh.pydata.org/en/latest/) - a Python library for creating interactive visualizations

[Dash](https://github.com/plotly/dash) - a Python library for creating web-based interactive dashboards

[D3](https://d3js.org/) - a JavaScript library for creating interactive data visualizations, tied to the DOM

[Vega](https://vega.github.io/vega/) - JSON/JavaScript-esque visualization language for creating interactive visualizations

[Leaflet](http://leafletjs.com/) - a JavaScript library for customizable, interactive maps. Very thorough and easy to work with!

[Folium](https://github.com/python-visualization/folium) - Python version of Leaflet. Doesn't have some of the more complex features but still good and easy to work with.

[Mapbox](https://www.mapbox.com/mapbox-gl-js/api/) - a JavaScript library for rendering interactive maps

[scikit-learn](http://scikit-learn.org/stable/) - a machine learning library for Python. Part of NumPy/SciPy/matplotlib ecosystem. Thorough and straightforward.

[TensorFlow](https://www.tensorflow.org/) - powerful Python-based machine learning framework

[Caret](http://topepo.github.io/caret/index.html) - machine learning package for R

[Jupyter Notebook](https://github.com/jupyter/notebook) - a web-based Python development environment/notebook. Very handy!

[Apache Zeppelin](https://zeppelin.apache.org/) - another web-based development environment/notebook. Can be used with many languages/kernels in the same notebook, including Spark

