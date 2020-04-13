# AirBnB-cities-comparison
AirBnB-cities-comparison is a collection of functions that can be used to compare B&Bs reviews around the world.

## Get the data
All listings can be downloaded from [insideairbnb](http://insideairbnb.com/get-the-data.html). <br/>
For all the cities to be considered, the relevant listings.csv.gz file has to be downloaded in the "Listings" folder. Naming convention: \<city_name\>.cvs.gz. <br/>
Files can be downloaded in the Jupyter Notebook as well. In order to do that, download links have to be manually updated in the "url_dict" dictionary.

## API
Following main features have been implemented:

- **Preprocessing** <br/>
Automated preprocessing of input data

-  **Geographical visualization** <br/>
Create dynamic maps of reviews distribution over the world or inside single cities

-  **Analysis of the influence of various features on review scores** <br/>
Analysis of how several B&B features (like property type and amenities) influence rating score. <br/>
Comparison of different cities using bar charts or color coded tables.

## Requirements
Following packages need to be installed in order to run the code in this directory:
- numpy
- pandas
- folium
- branca
- seaborn
- matlibplot
- sklearn
- os
- wget

## Additional information
This directory was created as part of the Udacity [Data Scientist Nanodegree](https://www.udacity.com/course/data-scientist-nanodegree--nd025) program. <br/>
The functions of this Jupyter Notebook were used to create the pictured used in this [Blog](https://medium.com/@enricooliva88/us-vs-europe-what-does-it-take-to-have-a-successful-b-b-84e82e393489).
