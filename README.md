# Analysing taxi trips in New York City

This repository stores the source code (in Rmarkdown) used for analysing the TLC Green Taxi Trips data from year 2014 to 2015. 

A key motivation of choosing to report in HTML document using [knitr](https://yihui.name/knitr/) is [reproducible research](https://en.wikipedia.org/wiki/Reproducibility#Reproducible_research) - in that the results are accompanied by the data and code needed to produce them. As such, the Rmarkdown files could be useful if one wishes to reproduce the exact same results of these studies.

## Visualization
Read the report [here](https://yaeba.github.io/nyc_taxi_trips_analysis/nyc_taxi_trips_analysis_visualization.html).

> The aim of this study is to gain an initial insight into the open source taxi and weather datasets for the year 2015 in the New York city. In the notebook, I will be dealing with millions of taxi trips data, performing initial exploratory data analysis on taxi usage and visualising the relationships with other attributes.

> In summary, I performed an initial analysis on the green taxi data that contains millions of trip records entire in R - in a reproducible manner. With ggplot and tmap, I depicted the relationship between attributes and geospatial visualization onto map of New York City taxi zones, and then attempted to answer a few questions for the study, using the figures and plots produced.

## Analysis
Read the report [here](https://yaeba.github.io/nyc_taxi_trips_analysis/nyc_taxi_fares_analysis.html)

> The aim of this project is to make a qualitative analysis and gain insights into the open source New York City Taxi and Limousine Service Trip Record Data. In the notebook, I will tackle a research problem and perform analysis on millions of taxi trips data.

> In short, I performed an analysis on taxi fares using the green taxi data that spans from year 2014 to 2015 entirely in R - in a reproducible manner. I reported the taxi fare and its relation with other attributes as an attempt to shed light and infer the hypotheses proposed. Then, statistical models were fitted on training set and evaluated using validation set, each of which contains 3 million records each. Models were then compared, interpreted and a final model was chosen after refining the models. Finally, suggestions for further improving the performance were given.
