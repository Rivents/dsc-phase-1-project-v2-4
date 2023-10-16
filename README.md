# Overview

Microsoft is planning to launch and develop a new movie studio to develop a new source of revenue and profit.

Analayzing publically available databases on thousands of films, we have a strong understanding of some of the variables that makes it a strong return on investment. 

# Business Understanding

What consitutes sucessful? there are many measurements of sucess that could be used in this senario. For simplicity, we have opted to use gross foreign reveanue as our bench mark of sucess. 
As far as what factors equate to higher grossing film worldwide, there are many to consider. Some of these include: 

* What movie types or **genres** being in the most revenue?

* What **studios** are the most profitable?

* How long should each movie be approximately in **length**?

# Data Understanding 

There are several publically data sets that were used for this analysis:

* [Box Office Mojo](https://www.boxofficemojo.com/)

* [IMDB](Imdb.com)

The Box Office Mojo primarily consisted of film title, gross domestic revenue, gross forgien revenue, and studio.
The IMDB database contains detailed information regarding film title, languages, genres, ratings, and casting.


# Methods

We evaluated these databases for several metrics that could be associated with larger market revenue.

* Movies across all time ranges were included

* We did not include movies with: *the number of votes less than 100* or *missing entries*

* Due to the numerous number of studios and genres each movie each could be attributed, only the top 10 genres and top 15 studios were evaluated for simplicity.


# Data Analysis

Using the data sample lsited above, we analyzed it for trends in movie genre, run time, and studio.

![graph of gross foreign reveanue over movie genre](https://raw.githubusercontent.com/Rivents/dsc-phase-1-project-v2-4/master/Genre%20chart.png)

![graph of gross foreign reveanue over movie studio](https://raw.githubusercontent.com/Rivents/dsc-phase-1-project-v2-4/master/Studio%20chart.png)

![Scatter plot comparison of gross foreign reveanue over movie runtime ](https://raw.githubusercontent.com/Rivents/dsc-phase-1-project-v2-4/master/Runtime%20scatter.png)


# Conclusion

Based on our analysis, we have determined in order to develop a movie with the most sales it should:

1. Have the Genre: **Sci-fi**, **Adventure**, or **Animation** - as they are the genres that generate the most foreign gross revenue

2. Be developped by **HC**, but if not, **P/DW**, **BV**, or **GrtIndia** are other good options

3. Finally, as far as runtime, the movie should on the longerside, from **100 to 150 minutes**

# Future direction

This evaluation can be further strengthened in a multitude of ways:

* Adjusting for inflation 
* Incorporating cost and looking at return on investment
* incporoating the effect of user imdb rating and 
* evaluating merchanizing and other revenue streams not directly from the box office


