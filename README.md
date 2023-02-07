### Ivy Phase 1 Project

### Business Problem

Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. You are charged with exploring what types of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

### Business Problem Understanding
In the following analysis, I will be exploring data from IMDB and the BOM .
I will be getting infomation regarding the following;Title, year, tconst(unique movie identifier),studio, domestic gross, foreign gross, average rating, number of votes and the movie genres
I will be focusing on both domestic and foreign gross for this analysis in order to get an understanding not only locally but also internationally

###### What questions were asked during the analytics process?
* What genres of movie are likely to succeed?
* Do multiple genre movies perform better than single genre movies?
* Is there a correlation between how movies perform domestically and internationally?
* Is there a correlation between how long a movie is run and how it is rated?
* Does the studio producing a movie determine how much gross the movie makes?

### The following steps were used in the analysis
* Data Extraction
* Data Cleaning
* Data Wrangling
* Data Analysis
* Action

### Data Extraction 
The following csv files were extracted for this analysis

* imdb.title.basics.gz
* imdb.title.ratings.gz
* bom.movie_gross.gz

### Data cleaning
The following unclean data was dealt with using appropriate methods
* Missing Data
* Wrong Data Types
* Outliers and non relevant data
* Duplicates

Methods applied during cleaning of this data include
* Dropping missing values
* Using mean to fill in missing values

![Uploading image.png…]()

* Assigning appropriate data types 
* Dropping duplicated values and columns

### Data Wrangling
In this step various methods were applied in order to make the data better for analysis and visualisation.
Merging Data to form one data frame
![Uploading image.png…]()

* Combining Data
* Joining Data
* Indexing Data
* Dealing with Categorical Data


### Data Analysis
Appropriate methods were applied in order to come up with various models and visualizations that will be used for coming up with appropriate actions to be undertaken by Microsoft movie studio before unveilling
Seaborn was used to visualise the various statitistical visualization models
![Uploading image.png…]()



### Action
From the visualizations various ctions were established to help Microsoft movie studio come up with a succesful movie studio 

Various actions were established to propell the success of the movie studio but few will be highlighted. They are:
#####* At the beginning, Microsoft should focus on genres News, Documentary and music as they have the highest individual ratings
#####* Microsoft should produce movies that  have multiple genres instead of one as they're more succesful and have a higher rating.


## Summary

To propell the success of Microsoft as they are unveiling their new movie studio , Data from three data sets was extracted, The data sets then underwent cleaning then wrangling . After wrangling the Data was used to create various statistical models and visualizations in order to establish appropriate actions to be undertook by microsoft in their making of the movie Studio. Various actions were suggested and business recommendations were yielded in the process.

## Conclusion
Even though there is no particular set step when it comes to making a MOvie Studio it is paramount that the steps taken yield profits and positive reception from the audiences. It therefore imporant that Microsoft movie studios start with genres that have a high rating as it is a clear indication of positive response from the audience. it is also important  that the movies produced by microsoft studios should have a variety of genres per movie to ensure that these movies are more engaging 
Microsoft Movie Studio should also focus on intricacies such as how long the movie runs and how well it perfoms locally before it does internationally . Micrsoft movie studio should also focus on what makes some movie studios stand out that their movies are easily receptible and have higher ratings. It is not impossible to make a breakthrough with the movie studio, however focusing on the data is a good start to realize the success of the movie studio.
