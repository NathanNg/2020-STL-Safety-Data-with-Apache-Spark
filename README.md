# Exploring the 2018 City of Saint Louis public crime data with Apache Spark 2.3

The Saint Louis OpenData project contains hundreds of datasets for the city of Saint Louis. Open government data has the potential to increase the quality of life for residents, create more efficient government services, better public decisions, and even create new local businesses and services.

The notebook uses Apache Spark and SQL APIs to analyze the crime data dataset and provides an answer to couple questions below: 
* How many different types of calls were made to the Police Department?
* How many incidents of each call type were there?
* What is the most dangerous month in Saint Louis city?
* How many service calls were logged on July 4th?
* How many service calls were logged in the first week of January 2018?

Import [this notebook](https://github.com/NathanNg/2018-STL-Crime-Data-with-Apache-Spark/blob/master/stl-crime-data-notebook.ipynb) into Databrick community edition and create a free cluster with Apache Spark 2.3, Scala 2.11, and Python 3.0 version in order to run the code.  In the end, the notebook will save the file to S3 storage with Parquet format to increase performance and accessible.
