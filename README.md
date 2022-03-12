# Movies-ETL
## Project Overview
The project is to create an automated pipeline/tool for Amazing Prime Video hackathon to anticipate low budget movies being released that will become popular so Amazing Prime Video can buy the streaming rights. The data sources that were used in this project are Wikipedia data, Kaggle metadata and the MovieLens rating data but the data needs to be cleaned, transformed and loaded into an PostgreSQL database to do the analysis.  

This hackathon requires four deliverables:

Deliverable 1: Write an ETL Function to Read Three Data Files
<br/>
Deliverable 2: Extract and Transform the Wikipedia Data
<br/>
Deliverable 3: Extract and Transform the Kaggle data
<br/>
Deliverable 4: Create the Movie Database

<br/>

## Results

### Deliverable 1: Write an ETL function to read three data files 
In ETL_function_test.ipyn, the Wikipedia JSON, the Kaggle metadata and MovieLens csv files are uploaded and converted three separate Pandas DataFrames. 
![file_to_load](Screenshots/file_to_load.png)
![file_to_load](Screenshots/file_to_load.png)
![file_to_load](Screenshots/file_to_load.png)
<br/>

### Extract and Transform the Wikipedia data
We filtered out the TV shows, consolidated the redundant data, removed the duplicates and formatted the Wikipedia data.
<br/>

### Extract and Transform the Kaggle and rating data
Again, we consolidated the redundant data, removed the duplicates, formatted and grouped the data.\
The Kaggle and rating data were then merged with the Wikipedia movies DataFrame.

### Load the data to a PostgreSQL Movie Database
<br/>
<p align="center">
  <img src="https://user-images.githubusercontent.com/68669675/93714176-9c6dec00-fb26-11ea-976c-c7d21e2fee0b.png"> 
</p>
<p align="center">
  <img src="https://user-images.githubusercontent.com/68669675/93714179-9d9f1900-fb26-11ea-815d-d14fee9755a4.png"> 
</p>
<br/>
## Summary
The ETL function created collects and cleans movie data from different sources (Wikipedia JSON and Kaggle and ratings csv files). It transforms and merges the data and loads it into two updatable PostgreSQL dataset tables ready to be used by the hackathon participants for their analysis.
