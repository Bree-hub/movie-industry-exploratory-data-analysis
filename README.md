# Movie Industry: Exploratory Data Analysis



![](https://images.unsplash.com/photo-1440404653325-ab127d49abc1?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80)

## Project Overview

Microsoft has announced that they would like to get into the movie industry. They will be creating a studio, however they have no knowledge of the movie industry. My goal is to analyzes movie data to determine the features and factors that contribute to the success of a movie. The step involved will be to import,clean and analyze movie data from a variety of sources so that I can provide recommendations to Microsoft that will allow them to be successful in the movie industry

## Data

The data used for this project was compiled by Flatiron School, and it was pulled from the sources listed below. All tables were cleaned but not all were used in final analysis.

Box Office Mojo: https://www.boxofficemojo.com/

IMDB: https://www.imdb.com/

Rotten Tomatoes: https://www.rottentomatoes.com/

The Movie Database: https://www.themoviedb.org/

The Numbers: https://www.the-numbers.com/

In my analysis I explore and answer the following questions:

1.Which movie genres are most commonly produced and does quantity equate to higher gross return?

2.What is the best time of the year to release a movie?

3.Which studios are the top competitors?

## Which movie genres are most commonly produced and does quantity equate to higher gross return?

I first count the number of movies in each genre and plot those results on a bar graph.

Using the same groupby method, I select the average box office return for each genre. I use the median in this case as the mean is likely skewed by outliers. Outliers could either be movies with enormous profits or movies having negative profit.

![](https://github.com/Bree-hub/Phase-1-Project/blob/main/MovieCountbyGenre.png)

![Image Description](http://localhost:8888/view/images/MedianboxofficebyGenre.png)

Conclusion:Adventure, Action, Comedy, Drama, Sci-Fi and Animation have the highest box office returns and also drama, comedy, and Action dominate the quantity of movie genres produced

## What is the best time of the year to release a movie?

I first determine the months that see the most movie releases and then grouping by month, I select the Profit and Profit Margin columns so that we can see which months have the most financial success.

![Image Description](http://localhost:8888/view/images/CountbyMonth.png)

![Image Description](http://localhost:8888/view/images/profitandprofitmarginbymonth.png)

Conclusion: The months of May, June, July November and December top in terms of both median profit and profit mergin.

## Which studios are the top competitors?

I first merge the tn.movie_budgets and bom.movie_gross data frames.

By amount of movies made, Universal, Fox, and Warner Bros. are top 3 with over 100 movies made.

![Image Description](http://localhost:8888/view/images/Top20StudiosbyMovies%20Produced.png)

Dreamworks, Buena Vista, Universal, Fox, Warner Bros, and Paramount have the highest net profit all over 1.5 billion

![Image Description](http://localhost:8888/view/images/Top20Studiosbyprofit.png)

# Conclusion
In the brief analysis above, we looked at who our top competitors would be based on the amount of movies made and the average net profit of each studio, we determined which the best time of year to bulk release movies, and finally looked at which genres have had the highest average net profit. There are many more factors involved in making movies that we could dive into, but this gives us answers to some foundational questions for creating a successful movie.

## Recommendations
I recommend that Microsoft should focus their efforts on the top 6 most profitable movie genres: Adventure, Action, Comedy, Drama, Sci-Fi and Animation. A further recommendation to focus on Sci-Fi and Animation due to less competition and a higher opportunity to profit.

I recommend that Microsoft release the bulk of their movies,during the months of May, June, July, November and December

Microsoft should research the top competitor's best practices and try to build off the success of these well established studios such as Universal, Fox and warner brothers who not only in the quantity but also quality of movies bases on profit analysis.

## Future Work
As next steps, I would suggest the following:

With the ever increaing inflation cost, conduct furrther analysis to adjust using Consumer Price Index
Conduct further analysis on how to allocate the production budget, minimizing it but effectively. A more detailed financial analysis to say the least.
A further analysis on the production team, when it comes to hiring the creative team such as directors, photographers, cinematographers and script writers.
Analysis of additional revenue streamse e.g. merchandise. sequels and licencing.













