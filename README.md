# 311project

By Hung-Yi Chang (Michael)
Tasks and Approaches:
Obejctives:

1. Consider only the 10 most common overall complaint types. For each borough, how many of each of those 10 types were there in 2020?
2. Consider only the 10 most common overall complaint types. For the 10 most populous zip codes, how many of each of those 10 types were there in 2020?
3. Considering all complaint types. Which boroughs are the biggest "complainers" relative to the size of the population in 2020? Meaning, calculate a complaint-index that adjusts for population of the borough.

Data Sources

1. 311 Service Requests Data data/311_2020data.csv
2. The 2010 US Census Population By Zip Code data/zipcode_population.csv
3. New York City Zip Codes data/zip.csv
4. Boroughs of New York City details below
Apporaches:¶

Since we are only focused on several features (Boroughs, zipcodes, and complaint types, we will clean and filter these features from the data of 311 data, zipcode data, and population data by requirements (details in comments). Then we make use of pandas and matplotlib.pyplot libraries to visualize the results.