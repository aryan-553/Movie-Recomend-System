# Movie-Recomend-System
Build a movie recomend system, a basic model type of which is used by amazon netflix YT etc
I've used 2 types of recomend system
1. demographic- Provides generalized recommendation to every user
  IMdB weighted rating used--> wr=(v/(v+m)*r)+(v/(v+m)*c)
  v is number of votes of movie
  m is min votes needed to be in  the chart
  r is avg rating of the movie
  c is the rating across the report
  v and r in the dataset so we cal c and m
2. content based filter- suggestion are made based on a particular item
  for this we compute team frequency-inverse document frewuency but this built-in scikit
  
 we get root mean square value of about 89%
