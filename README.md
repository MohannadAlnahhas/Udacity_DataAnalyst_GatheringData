# Udacity_DataAnalyst_GatheringData
Date: 19/08/2020 <br>
In this project, I will gather some data from different sources of the top 100 movies all the time in rotten tomatoes website. Using Pandas, BeautifulSoup,  and other libraries from python. <br>
First of all, I have a zipped file contains 100 html files, each one corresponds to a movie. We will use BeautifulSoup to extract some information such as movie title, audience score, and number of audience ratings. The extracted information well then be converted to a data frame. <br>
Second, I was given 100 URLs of Ebert's review (movie critique). Using requests library, I will download the reviews and save them as text files, each text contains the review of a movie. Then I will make a new data frame that contains the movies and the review. <br>
Third, I will use library wptools to search for movies posters and download each movie poster to a folder. Resulting in a data frame that contains the movie name and poster URL. <br>
Finally, I will give an example to save one of the data frames as SQL database and or as a csv file.
