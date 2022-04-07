# Data Challenge 2 - Group 10
The data that was used to obtain all the results was retrieved from the street data CSVs from https://www.dropbox.com/s/zg8jlem8ly9v9vv/Jan_2010_Oct_2021.zip?dl=0. First a database was made of all the street data CSVs, then by performing queries on this database, we obtained CSV files which where used for the further analysis. This reduced the file size from a 15GB database to about 300MB CSV files. 
* In the file '1 Database Creation', the database is formed from by selecting all the street_crime CSVs.
* In the file '2 Query Database', the aggregated CSV files are created.
* In the file '3 Crime per county', the pipeline for predicting the number of crimes per district on the input of a police force.
* In the file '4 Crime type per county', the pipeline for predicting the number of crimes per crime type for a district. 
* In the file '5 Location suggestion', the notebook is shown for the detailed location analysis of crime. This shows the crime per zip code in a county. 
* In the file '6 Model performance 1', the notebook is given for the performance analysis of some of the investigated models
* In the file '7 Model performance 2', the notebook is given for the performance analysis of a couple more advanced models that we investigated. 
* In the file 'Queried datasets', the CSV files can be found, which are required to run all of the mentioned notebooks. Relative paths are used in the notebooks, so when running, make sure that the CSV files have the proper name and that CSV files are stored in the same folder as the notebook. These files are the same files that are created in '2 Query Database'. 

As for the requirements:
* All the modules that need to be imported are included in the notebooks. Some modules require installing (note that it might be necessary to create a new environment, to properly install these modules). The modules that require installing are:
* geopandas (for: '5 Location suggestion')
* pmdarima (for most other notebooks)
* xgboost (performance analysis notebooks)
