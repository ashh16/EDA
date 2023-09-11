Netflix Movies and TV-Shows EDA.

The dataset used for this EDA is the Netflix Movies and TV Shows dataset available on Kaggle. It contains information about movies and TV shows available on Netflix as of 2021. The dataset includes features such as:

•	Title: The title of the movie or TV show.
•	Type: Whether it's a movie or TV show.
•	Director: The director(s) of the movie or TV show.
•	Cast: The cast members.
•	Country: The country where the content was produced.
•	Release Year: The year of release.
•	Rating: The content rating.
•	Duration: The duration in minutes for movies or the number of seasons for TV shows.
•	Listed In: Genre(s) the content belongs to.
•	Description: A brief description of the content

Starting with EDA.

1)	Dataset Overview:
	Import Required Libraries
	Import Dataset
	Basic functions like head, info, shape, describe, rename etc

3)	Data Cleaning: 
In data cleaning phase we will firstly check if there are any null values. To deal with null values we can either remove null values or replace them with suitable variable. We can also convert the data into excel to check the updated processes.

5)	Analysis and visualization:
	Countplot of types of shows
	Piechart overall ratings given by rating systems
	Countplot of ratings given by rating systems
	Countplot of country-wise types of shows on Netflix(hue by shows)
	Countplot of types of show released every year
	Pie chart of country-wise shows production(in percent)
	Barplot of types and releaseyear
	Lineplot to compare types of shows year-wise

Summary 
•	Count of titles has increased significantly over the years.
•	Specifically, two type of titles are available on Netflix:'Movies' & 'Tv-shows'
•	Top most rating system is 'TV-MA' which has rated over 36.7% show (3207).
•	United States is the country with most release on Netflix with record of 2818 total shows followed by India, United Kingdom, Japan & South Korea.
•	United States has the largest production count with 46.6%
•	If you see the comparsiosn chart theres significant growth graph of TV-Shows during the year 2019-2020, covid pandamic is one of the biggest reasons for this change.


