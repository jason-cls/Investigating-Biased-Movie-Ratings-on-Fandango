# Investigating Biased Movie Ratings on Fandango
Past analysis from 2015 performed by [Walt Hickey](https://fivethirtyeight.com/features/fandango-movies-ratings/) had shown evidence that Fandango's rating system was biased in that movie ratings were rounded up and thus inflated to be higher than they actually were.
In this project, more recent movie rating data was analyzed to determine whether there had been any change in Fandango's rating system since Hickey's analysis.

Two data sets were taken into consideration in this project. The [first set of data](https://github.com/fivethirtyeight/data/tree/master/fandango) contains the movie ratings from 2015, while the [second set of data](https://github.com/mircealex/Movie_ratings_2016_17) contains movie rating data for popular movies in 2016 and 2017.

### Results
- KDE plots of Fandango movie ratings for seperate years illustrate a slight shift in the distribution of Fandango's star ratings between 2015 and 2016.
- Average Fandango ratings were higher in 2015 compared to 2016.

### Libraries used
- pandas
- numpy
- matplotlib
- seaborn
