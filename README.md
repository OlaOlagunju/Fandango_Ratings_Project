# Analyzing the Inflation of Fandango Ratings from 2015-2017

## Summary
In this project, we investigated Fandango movie ratings. The ratings go from zero to five stars, in increment of 0.5 stars. In this [article](https://fivethirtyeight.com/features/fandango-movies-ratings/), Walt Hickey found out that the ratings displayed on Fandago's website were higher than the actual ratings. More precisely:
- The rating was almost always rounded up to the next multiple of 0.5. For example, 4.1 would be rounded to 4.5 instead of 4.
- In 8% of the ratings he analyzed, the rouding was to the nearest whole star. For example, 4.5 to 5 stars.

The article was written in 2015. The goal for this project was to determine if Fandango reacted to this article and changed its rating methodology in 2016.

To do this, we explored two data sets:
- fandango_score_comparison.csv: Characteristics of the rating system before Hickey's analysis, you can find document [here](https://github.com/fivethirtyeight/data/tree/master/fandango).
- movie_ratings_16_17.csv: Characteristics of the rating system after Hickey's analysis, you can find document [here](https://github.com/mircealex/Movie_ratings_2016_17).

From our results, we saw a left shift in the ratings from 2015 to 2016. This was mainly due to less 5 and 4 stars ratings, and more 4 and 3.5 stars ratings. 

This could be explained by Fandango changing their rating algorithm. Indeed, we compared the shift from 2015 to 2016 and the shift from displayed ratings and actual ratings in 2015, and they look similar. However, as our sample size is relatively small, we cannot exclude that this is simply due to other extrinsic factors in movie ratings between 2015 and 2016. 

![]()
![]()
![]()
