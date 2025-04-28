# Spotify-Analysis

# Summary 
In this project I will attempt to create a music recomendation model using data for songs from 1950 through 2020 covering 7 different genres. Each songs is described by it's topic, the topics include: dating,violence,world/life,night/time,shake the audience,family/gospel,romantic,communication,obscene,music,movement/places,light/visual perceptions,family/spiritual,sadness, and feelings.

# Exploratory Data Analysis
-The Univariate analysis showed that the genre with the most representation in the datafram were Pop, Country, and Blues. The songs that were least represented were Reggae and hiphop, which isn't surprising since both Genres did not exist until after the 1960's. The topics that were most reoccuring were Sadness, violence, world\life and Ocbscene

- The Bivariate analysis showed that pop and country had the higest perecntage of the songs with Obscene and violent topics. Rock had the highest number of songs with violent topics with pop following at a close second. Hip hop has the least amount of songs with multiple topics, the most reperesented topic in hip hop was obscene.

- the Multivariate analysis showed that there was a lot of jazz music being release between the 1950 and 1960. These songs covered a large range of topics. As the timeline got closer to 2020 the number of obscene songs had increased drastically and were the most repesented topic for 2010 - 2020.

# Cleaned_Data

The columns that had object data types were dropped from the datafram becuase they couldn't be used for the modeling. The unnamed: 0 and release_date columns were also dropped becuase they didn't provide any relevant information that would make the modeling or prediciton more accurate.

# modeling

For the modeling I did an elbow plot and silhouette polt with and without scaling. Based on the result from the plots I determined how many clusters were present in the dataframe and used that for my prediciton. I used PCA to better show the clusters and then I labled what topic each cluster represented.