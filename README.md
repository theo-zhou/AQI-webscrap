# AQI-webscrap
Using GET requests and API to scrap air quality data and store into MongoDB
### Final Project for BAX422: Data Design and Representation

We first used CloudAPI to scrap daily air quality data and geospatial information from aqicn.org from three cities: Beijing, Shanghai, Chongqing

Then direct GET request to extract the weather information in the same cities. 

When deisgning database structures, Mongodb was chosen with its high flexibility and we indexed on geospatial coordinates as a framework for potential query purpose.

Also we performed simple data analysis comapring the different cities as well as the weather impacts on air quality. 
