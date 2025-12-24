Netflix dataset from Kaggles is cleaned and analysed to answer a few questions of interest 

The questions are as follows:

What is the distribution of movies vs. TV shows over time? To answer this question we need the count of movies and TV shows which can be extracted from 'Type' column and we also need time which can be extracted either from 'date_added' or 'release_year', we'll decide the best one further while coding. The best visualization would be a Time series chart.

Which countries contribute most to Netflix’s movies and shows? To answer this question we can plot two different geographical maps one for movies and another for Tv shows. Now we will need a feature that can provide the details of geographical location of the movie's origin, the 'country' coulmn is best suitable for this.

How have content ratings (TV-MA, PG-13, etc.) change over time? To answer this question we need the 'rating' column and the 'date' or 'release_year' column and we can plot a line graph to observe the change.

Are there seasonal trends in releases? To answer this question we can plot a bar chart to see the trends along the month/time of the year. We can use 'date_added' column for this.

