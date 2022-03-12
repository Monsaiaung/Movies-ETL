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

<br/>

### Deliverable 2: Extract and Transform the Wikipedia data
In ETL_clean_wiki_movies.ipynb, we cleaned out the TV shows, removed the duplicates and formatted the Wikipedia data.
<br/>

### Deliverable 3: Extract and Transform the Kaggle and rating data
In ETL_clean_wiki_movies.ipynb, we removed the duplicates, formatted and grouped the data. Then we merged Kaggle_metadata dataframe and wiki_movies dataframe and named it movies_df.

### Deliverable 4: Create the Movie Database
Lastly, in ETL_create_database.ipynb, we finalized the movie dataframe. Afterwards, we run a query on the PostgreSQL database to get the number of rows for the movies and ratings tables.
