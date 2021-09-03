# Simple-recommender
## A simple recommender to recommend top movies using metadata collected from IMDB.

Simple recommenders are basic systems that recommend the top items based on certain metric or score.

The metric used here is called the 'Weighted Score'

Weighted Rating(WR) = { (v/v+m) * R } + { m/(v+m) * C } 

* v is the number of votes for the movie
* m is the minimum votes required to be listed in the chart
* R is the average rating of the movie
* C is the mean vote across the whole report

