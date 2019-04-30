
# Investigate a Dataset (TMDb movie data)

***Investigate-a-dataset***

In this project, I analyze a dataset and communicated my findings about it. I used the Python libraries NumPy, Pandas, and Matplotlib to do the analysis

This Python script is written for Project 3 (Term 1) of Udacity's Data Analyst Nanodegree (DAND) and is used to explore TMDb movie data. But what determines if a movie is considered as good or bad? There could be several factors influencig the quality of a movie, as for example the budget, genre, etc. This little project helped the author to improve his data analytics skills and explore some of the success criteria for movies.

First some Data Wrangling was applied, before the data was cleaned in order to perform Exploratory Data Analysis.



***Method to run the script:***

I can run the script using a Python integrated development environment (IDE). This script is written in Python 3, so you will need the Python 3.x version of the installer. The code was written in Jupyter Notebook.

***Datasets***

This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue.

Certain columns, like ‘cast’ and ‘genres’, contain multiple values separated by pipe (|) characters. The final two columns ending with “_adj” show the budget and revenue of the associated movie in terms of 2010 dollars, accounting for inflation over time.

Variables:

1)id

2)imdb_id

3)popularity

4)budget

5)revenue

6)original_title

7)cast

8)homepage

9)director

10)tagline

11)keywords

12)overview

13)runtime

14)genres

15)production_companies

16)release_date

17)vote_count

18)vote_average

19)release_year

20)budget_adj

21)revenue_adj


Here I have taken tmdb.csv file for the manuoulation of the project.


# Findings:

Various findings are calculated from the project they are as follows:

1)Movies which had most and least profit
2)Movies with largest and lowest budgets
3)Movies with most and least earned revenue
4)Movies with longest and shortest runtime
5)Year of release vs Profitability

# Conclusions:

This was a very interesting data analysis. We came out with some very interesting facts about movies. After this analysis we can conclude following:

For a Movie to be in successful criteria

1.Average Budget must be around 60 millon dollar

2.Average duration of the movie must be 113 minutes

3.Any one of these should be in the cast :Tom Cruise, Brad Pitt, Tom Hanks, Sylvester Stallone,Cameron Diaz

4.Genre must be : Action, Adventure, Thriller, Comedy, Drama.

By doing all this the movie might be one of the hits and hence can earn an average revenue of around 255 million dollar.

Limitations: This analysis was done considering the movies which had a significant amount of profit of around 50 million dollar. This might not be completely error free but by following these suggestion one can increase the probability of a movie to become a hit. Moreover we are not sure if the data provided to us is completel corect and up-to-date. As mentioned before the budget and revenue column do not have currency unit, it might be possible different movies have budget in different currency according to the country they are produce in. So a disparity arises here which can state the complete analysis wrong. Dropping the rows with missing values also affected the overall analysis.

# What I learned

1)What all steps are involved in a typical data analysis process.

2)Comfortable posing questions that can be answered with a given dataset and then answering those questions.

3)Know how to investigate problems in a dataset and wrangle the data into a format that can be used.

4)Have practice communicating the results of the analysis.

5)Being able to use vectorized operations in NumPy and Pandas to speed up your data analysis code.

6)Being familiar with Pandas Series and DataFrame objects, which lets access data more conveniently.

7)Last but not least, Know how to use Matplotlib and Seaborn to produce plots showing findings.
