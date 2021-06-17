# Written Analysis of Movies ETL 

## Overview of Project
The objective of Movies-ETL is to write an ETL function that reads three separate datafiles and converts them into their own dataframes. The idea is simply to take data from outside sources and put them into one place, which is conceptually a simple task especially since all the datafiles have somewhat similar data. The movies.csv, ratings.csv, and wikipedia JSON files are where we draw the data from to form three concise dataframes. 

### Resources
**Source of Data** : movies.csv, ratings.csv, wikipedia-movies.json

**Software** : Python 3.7.6 , Jupyter Notebook, Visual Studio Code.
## Results

### ETL_function_test Results 
Wiki_movies_df
![part1](https://user-images.githubusercontent.com/82983000/122411824-136bd000-cf53-11eb-8a45-6c454d55f871.png)
kaggle_metadata
![part2](https://user-images.githubusercontent.com/82983000/122411872-1d8dce80-cf53-11eb-8786-e119e672a381.png)
ratings
![part3](https://user-images.githubusercontent.com/82983000/122411899-21b9ec00-cf53-11eb-8178-c3007b31ca93.png)

### ETL_clean_wiki_movies Results
wiki_movies_df
![part4](https://user-images.githubusercontent.com/82983000/122412448-92f99f00-cf53-11eb-826f-1bb36d969f64.png)
wiki_movies_df (columns)
![part5](https://user-images.githubusercontent.com/82983000/122412525-a442ab80-cf53-11eb-81f2-a5d9a6f810e8.png)


### ETL_clean_kaggle_data Results 
movies_with_ratings_df

![part6](https://user-images.githubusercontent.com/82983000/122413234-35b21d80-cf54-11eb-9ca7-24fa5bb6edd8.png)

movie_df

![part7](https://user-images.githubusercontent.com/82983000/122413293-41054900-cf54-11eb-86c0-ebb911e7fd2f.png)

## Summary
movies_metadata (ETL_create_database)

![part8](https://user-images.githubusercontent.com/82983000/122413638-89bd0200-cf54-11eb-83d4-fd95e676ab5d.png)


