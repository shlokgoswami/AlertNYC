# AlertNYC
This repository contains the code and documentation for the AlertNYC Big Data Final Project. The project combines PySpark, MongoDB, and various Python libraries to analyze the NYPD Complaints dataset (https://data.cityofnewyork.us/Public-Safety/NYPD-Complaint-Data-Historic/qgea-i56i) and gain insights into crime patterns in New York City.

Project Overview
The AlertNYC project aims to provide comprehensive insights into crime patterns within specific neighborhoods in New York City. The project utilizes PySpark, a distributed data processing framework, to efficiently process and analyze the large NYPD Complaints dataset sourced from NYC Open Data. The data is cleaned, merged with NYC neighborhood data, and loaded into MongoDB for further analysis.

## Project Setup
To set up the project, the following technologies and libraries were used:

PySpark: A distributed data processing framework for efficient processing of large datasets.
PyMongo: A Python library for interacting with MongoDB, a popular NoSQL database.
Pandas: A powerful data manipulation and analysis library in Python.
Geopy: A Python library for geocoding and reverse-geocoding capabilities.
Folium: A Python library for visualizing geospatial data.
Haversine: A Python library for calculating distances between two points on a sphere.
Matplotlib: A popular data visualization library in Python.
Seaborn: A statistical data visualization library built on top of Matplotlib.

The project architecture involves data profiling, data preparation and cleaning, data merging, data storage in MongoDB, and performing various analyses using MongoDB's aggregation framework. The results are visualized using Matplotlib, Seaborn, and Folium libraries.

![Diagram](https://github.com/shlokgoswami/AlertNYC/raw/main/Blank%20diagram.png)


## Limitations and Future Work
While the project provides valuable insights into crime patterns in New York City, there are some limitations to consider. These include:

Reliance on the quality and completeness of the NYPD Complaints dataset.
Limited timeframe of the data (2006 to 2020) that may not capture recent changes or emerging trends.
Specificity to New York City, which may not be applicable to other regions or cities.
Potential errors or discrepancies introduced during the data merging process.
Lack of comprehensive information on offender characteristics.
Future work on the project could focus on:

Incorporating real-time or near real-time data streams for up-to-date crime trends.
Predictive analytics to develop models for forecasting crime hotspots.
Exploring the correlation between crime rates and socioeconomic factors.
Comparative analysis with other cities or regions for benchmarking.
Integration of additional data sources, such as emergency service response times or demographic data.
Advanced spatial analysis techniques and visualization methods for deeper insights.

## Conclusion
The AlertNYC project demonstrates the power of big data analytics in uncovering valuable insights from large datasets. By analyzing the NYPD Complaints dataset, the project provides insights into crime patterns, helping with decision-making processes related to crime prevention and law enforcement in New York City. The repository contains the code, documentation, and visualizations to support the project's findings.
