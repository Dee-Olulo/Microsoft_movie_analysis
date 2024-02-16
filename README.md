# Microsoft_movie_analysis
![Data_visualisation - Jupyter Notebook - Google Chrome 2_15_2024 11_06_43 PM](https://github.com/Dee-Olulo/Microsoft_movie_analysis/assets/151445934/92e877a4-7d1c-4456-aed8-047e9441fcb5)
##### Author : Diana Olulo
## Overview
This project aims to analyze the needs of Microsoft, a company interested in starting a movie studio despite lacking experience in film production. The descriptive analysis conducted explores relationships between runtime, popularity, genre, revenue, and ratings. Findings indicate that drama is the most popular genre, with Action/Adventure/Drama generating the highest revenue. The average duration of movies is 90 minutes. Microsoft can leverage this analysis to make informed decisions in movie production.

## Business Problem
Microsoft aims to enter the realm of original video content creation, inspired by the success of major companies in this domain. Their decision to establish a new movie studio presents a challenge due to their lack of expertise in the film industry. Consequently, they've enlisted your expertise to delve into the current trends in the movie industry and distill actionable insights. Your team's objective is to identify the most successful film genres at the box office and provide recommendations to guide Microsoft's new movie studio in determining the types of films to produce.

## Data
The datasets utilized for this analysis are sourced from Box Office Mojo, IMDB, Rotten Tomatoes, and TheMovieDB.org. These platforms provide essential information necessary for conducting a comprehensive analysis. The dataset includes data points such as runtime_minutes, popularity, genres, production budget, worldwide gross revenue, and ratings, among others.

## Methods
Regression analyses were conducted to examine the relationship between worldwidegross and various factors including genre, runtime, popularity and budget. By analyzing these factors, we aim to identify optimal choices for Microsoft's movie studio. The process involves iterating through different metrics until we arrive at a comprehensive recommendation regarding the type of movies to produce.

## Results

The graph also includes a cumulative distribution line that shows the percentage of movies that have a worldwide gross below a certain amount. For example, approximately 75% of movies have a worldwide gross below 200, while 95% of movies have a worldwide gross below 400.

![Data_visualisation - Jupyter Notebook - Google Chrome 2_16_2024 10_10_12 PM](https://github.com/Dee-Olulo/Microsoft_movie_analysis/assets/151445934/2794fa77-98d4-4810-91a2-67677614a06e)


The graph  below depicts that the Action genre yields the highest revenue, around 1.25 billion dollars, followed by Comedy, Drama, and Adventure genres with revenues of approximately 750 million, 500 million, and 400 million dollars respectively.

![Data_visualisation - Jupyter Notebook - Google Chrome 2_16_2024 9_14_21 AM](https://github.com/Dee-Olulo/Microsoft_movie_analysis/assets/151445934/83b6bddc-61e5-4b21-b5a1-cd563f1f3580)

Based on the graph below, we can observe that the Comedy genre has the highest median rating (approximately 7), followed by the Drama, Romance, and Documentary genres with a median rating of around 6. The Horror and Thriller genres have a lower median rating (approximately 5).

![Data_visualisation - Jupyter Notebook - Google Chrome 2_16_2024 9_29_53 AM](https://github.com/Dee-Olulo/Microsoft_movie_analysis/assets/151445934/fa54eb8e-69ac-4d89-a592-6db4ab40f80e)

Based on the graph, we can observe that most movies have a production budget between 0 and 30 million dollars. The peak of the density plot is around 15 million dollars, indicating that this is the most common production budget for movies in the dataset. The graph also shows that there are some movies with very high production budgets, with a few movies having budgets of over 100 million dollars.

![Data_visualisation - Jupyter Notebook - Google Chrome 2_16_2024 9_38_31 AM](https://github.com/Dee-Olulo/Microsoft_movie_analysis/assets/151445934/b271e379-4788-4e4c-a87c-0061669a19b7)

The heatmap reveals significant correlations: popularity and worldwide gross (0.57), larger budgets and higher gross (0.41), while longer runtimes tend to slightly lower vote averages (-0.12). This suggests focusing on popular genres with moderate budgets for optimal returns.


![Data_visualisation - Jupyter Notebook - Google Chrome 2_16_2024 10_22_31 AM](https://github.com/Dee-Olulo/Microsoft_movie_analysis/assets/151445934/27b5d26e-850e-4d34-93c1-6415bcaf4b81)

## Conclusion

###### The analysis leads to the following recommendations:
1. Microsoft should aim for movie runtimes between 90 and 125 minutes.
2. The production budget should fall within the range of 15 to 30 million dollars.
3. Microsoft should prioritize producing more comedy, drama, action, and adventure movies, as they are popular and generate high revenue.







