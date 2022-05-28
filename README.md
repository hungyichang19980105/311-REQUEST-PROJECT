<h1><center>311 Request Data Project</center></h1>
<h3><center>By Hung-Yi Chang (Michael)</center></h3>
<h3>Tasks and Approaches:</h3>
<p>
    <h6>Obejctives:</h6><br>
    1. Consider only the 10 most common overall complaint types. For each borough, how many of each of those 10 types were there in 2020?<br>
    2. Consider only the 10 most common overall complaint types.  For the 10 most populous zip codes, how many of each of those 10 types were there in 2020?<br>
    3. Considering all complaint types. Which boroughs are the biggest "complainers" relative to the size of the population in 2020? Meaning, calculate a complaint-index that adjusts for population of the borough.<br>
    <br>
    <h6>Data Sources</h6><br>
    1. <a href="https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2010-to-Present/erm2-nwe9">311 Service Requests Data</a> data/311_2020data.csv<br>
    2. <a href="https://blog.splitwise.com/2013/09/18/the-2010-us-census-population-by-zip-code-totally-free/">The 2010 US Census Population By Zip Code</a> data/zipcode_population.csv<br>
    3. <a href="https://www.nycbynatives.com/nyc_info/new_york_city_zip_codes.php">New York City Zip Codes</a> data/zip.csv<br>
    4. <a href="https://en.wikipedia.org/wiki/Boroughs_of_New_York_City">Boroughs of New York City</a> details below<br>
    <h6>Apporaches:</h6><br>
    Since we are only focused on several features (Boroughs, zipcodes, and complaint types, we will clean and filter these features from the data of 311 data, zipcode data, and population data by requirements (details in comments). Then we make use of pandas and matplotlib.pyplot libraries to visualize the results.
</p>
