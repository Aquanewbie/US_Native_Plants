## US_Native_Plants ##
## Summary ##
Create a MongoDB database via Python's pymongo. Create functions to query the database per State and Genus, and plot bar charts of Count of Species Per State. <br/>

## Methods ##
Connect to Mongo and define a database.
Loop through State CSV Files and define state dataframes. 
Parse the 'Scientific Name with Author' value and extract the first to words on the string (Genus, Species). 
Create Fuctions to query Mongo Database by changing State and Genus sought to query. 

#Visualizations
<img src="/Visualizations/CalamagrostisSpeciesPerState.jpg" width =700> </br>
<img src="/Visualizations/CarexSpeciesPerState.jpg" width =700> </br>
<img src="/Visualizations/MiscanthusSpeciesPerState.jpg" width =700> </br>
<img src="/Visualizations/MuhlenbergiaSpeciesPerState.jpg" width =700> </br>

## MongoDB ##
-The Plant Database is formatted by State Collections of Records of Locally Occuring Plants and Described Plants.

## Objectives: ##
-Compile State Native Plant Data From the USDA State PLANTS Checklist.<br/>


## Data Sources: ##

State Plant Data in the form of CSVs are sourced from the USDA's Natural Resources Conservation Service. <br/>
https://plants.sc.egov.usda.gov/dl_state.html<br/>


