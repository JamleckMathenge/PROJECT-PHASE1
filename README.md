# PHASE 1: INDIVIDUAL PROJECT.     
# PROJECT INTRODUCTION.
This project entails research that uses exploratory data analysis from (“zippedData”)  to generate insights on creating a new movie studio by Microsoft.
# PROJECT OVERVIEW.
In the conceptualization of this project, I assumed the role of a Data Scientist at Microsoft. This project entails a comprehensive understanding and analysis of movies from (“zippedData”) to come up with business-related recommendations for the head of Microsoft on the creation of a new movie studio. The main purpose of this project is to make use of exploratory data analysis to acquire information required to recommend appropriate actions by Microsoft on the creation of the new movie studio. This project is supplemented by visualizations to assist in the conceptualization of the findings.
# BUSINESS UNDERSTANDING.
The key objective of this project is to formulate data-backed recommendations for Microsoft in the creation of the new movie studio. Throughout this project, as a Data Scientist, I intend to formulate various key recommendations that will answer the following business questions.
# 1.Which directors should Microsoft Studio employ in creation of movies?
# 2.Which writers should Microsoft Studio employ in creation of movies?
# 3.What is the best runtime range for movies?
# 4.Which are the most preferred movie genres among movie fans?
# 5.In which regions should Microsoft studio focus its movie marketing efforts?
# 6.How does the movie ordering affect the number of movies watched?
# DATA COLLECTION.
The data used in this project was collected from various sources including Box Office Mojo, IMDB, Rotten Tomatoes, TheMovieDB, and The Numbers, and compiled into a folder (“zippedData”). From the folder, I chose to use the recommended data sets which include: The ("zippedData/im.db") database and ("zippedData/bom.movie_gross.csv.gz") CSV file.

# DATA DESCRIPTION.
# The ("zippedData/im.db")database contains 8 tables including: movie_basics, directors, known_for, movie_akas, movie_ratings, persons, principals and writers.
The tables contain numerous data from various sources in the following shapes;
1. Principals - It has 1028186 rows and 6 columns.
2. Persons - It has 606648rows and 5 columns.
3. Known_for - It has 1638260 rows and 2 columns.
4. Directors - It has 291174 rows and 2 columns.
5. Writers  - It has 255873 rows and 2 columns.
6. Movie_basics - It has 146144 rows and 6 columns.
7. Movie_ratings  - It has 73856 rows and 3 columns.
8. Movie_akas - It has 331703 rows and 8 columns.
# The ("zippedData/bom.movie_gross.csv.gz") CSV file contains a table with data about movies.
The table has 3387 rows and 5 columns.
#The ("zippedData/tmdb.movies.csv.gz") CSV file contains a table with data about movies.
The table has 26517 rows and  10 columns.
#The ("zippedData/tn.movie_budgets.csv.gz") CSV file contains a table with data about movies.
The table has 5782 rows and 6 columns.
# DATA CLEANING.
The main purpose of data cleaning is to prepare the data for analysis which will then be useable to answer our project questions. Data cleaning was also done to ensure the validity, accuracy, completeness, consistency, and uniformity of the data.I then selected the tables that I would use as the basis for my recommendations. I then cleaned the tables selected using the following steps:
# TASK1:The first task was to check if the column names were uniform and readable. 
# TASK2: The second task was to check for duplicated rows. 
# TASK3:The next task was to check if there were missing values. 
# TASK4:The next task was to decide how to deal with the missing values. (Either drop if they are unnecessary or replace the missing values with the best fit.
# TASK5: The last task was to check if the data types of the columns were correct.(If the data type was wrong I corrected it.
# EXPLORATORY DATA ANALYSIS.
In this section, I investigated the data sets I intended to use in order to create visualizations that would act as the base of my recommendations.
# VISUALISATION 1
# ![image](https://user-images.githubusercontent.com/110511316/187027786-48a00a8f-38dc-423c-96ac-906ab08ceaa4.png)
This bar chart shows the best directors in the movie industry. I only took into consideration movies that had above 1000 votes so as to ensure that the average rating was a clear indication of what movie fans think about a certain movie.
# VISUALIZATION 2.
# ![image](https://user-images.githubusercontent.com/110511316/187027863-7f3bc00b-3596-45d4-8280-1a8de82e8d7d.png)
This bar chart shows the best writers in the movie industry. I only took into consideration movies that had above 1000 votes so as to ensure that the average rating was a clear indication of what movie fans think about a certain movie.
# VISUALISATION 3.
# ![image](https://user-images.githubusercontent.com/110511316/187027893-98056a01-a476-4b80-8e28-8625fc0b0f19.png)
The histogram above shows the runtime in minutes of the movies that had an average rating of above 7 and had a minimum of 1001 votes. This was to show what is the best runtime of a movie especially movies that have a high rating.
# VISUALIZATION 4.
# ![image](https://user-images.githubusercontent.com/110511316/187027918-7a96d5e8-f394-49d8-b6bb-a78015d87d11.png)
In the bar chart above, I have shown the relationship between the Top rated genres against the number of movies that had an average rating of above 7 and at least 1001 votes. I did this to show which are the most watched among the top-rated genres.
# VISUALIZATION 5.
# ![image](https://user-images.githubusercontent.com/110511316/187027936-e443eda7-2f42-44a3-bf8b-76200c667ce4.png)
The bar chart above shows the regions with the most movie fans based on the number of movies watched per region. I did this visualization to show the relationship between each region and the popularity of movies in the regions.
# VISUALIZATION 6.
# ![image](https://user-images.githubusercontent.com/110511316/187027953-456cae72-9948-4300-974a-59b71802e538.png)
The bar chart above shows the relationship between movie ordering and the number of movies watched. It shows that the number of movies watched reduces as the ordering increases.
# RECOMENDATIONS.
# From visualization 1, I recommend that Microsoft Studio employ directors who feature in the figure based on their availability and rating showed by the figure. This is because they have directed the movies with the best rating among movie fans. 
# From visualization 2, I recommend that Microsoft Studio employ writers who feature in the figure based on their availability and rating showed by the figure. This is because they have helped create the movies with the best rating among movie fans. 
# From visualization 3, I recommend that Microsoft Studio should create movies that have a runtime in the range of (100-125 minutes) . This is because my analysis has concluded that most of the top rated movies have a runtime in this range.
# From visualization 4, I recommend that Microsoft Studio should focus on the following movie genres (Drama, Documentary, Comedy-Drama, Drama-Romance, Comedy-Drama-Romance). This is because among the top rated movies this genres feature the most.
# From visualization 5, I  recommend that Microsoft Studio should focus their movie marketing in the following regions (US,  XWW, RU, DE, FR). This is because they are the regions with the most movie fans.
# From visualization 6, I recommend that Microsoft Studio should create movies with as little ordering as possible. This is because I found out in my analysis that the number of movies watched is inversely proportional to increase in ordering.
#CONCLUSION.
During this project, I dedicated my time and efforts to answer various business questions that have helped me come up with recommendations for Microsoft Movie Studio. This project is backed by analysed data to prove the accuracy and correctness of my recommendations.
