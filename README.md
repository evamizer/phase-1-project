# Phase 1 Project - Making Microsoft Movie Magic


##### Author: Eva Mizer

In this project, we will assess different aspects needed to take into consideration when opening a new movie studio using coding, math, and data analysis! 

Feel free to skip ahead via these links:

* [***Project Overview:***](#project-overview) The project goal, audience, and dataset
* [***Business Problem:***](#business-problem) The client, the endgoal, and the objective
* [***The Data:***](#the-data) The data sets I used
* [***The Process:***](#the-process) Data sorting and cleaning I utilized
* [***Results:***](#results) Data sorting and cleaning I utilized

## Project Overview

For this project, we will use exploratory data analysis to generate insights for a business stakeholder that wants to expand their current portfolio and crate a movie studio. This will have them have a better plan to go forward and get the most for their investment.

## Business Problem

Microsoft wants to enter the movie making business! They want to make a splash and get an idea of where to start budgeting, creating, and allocating a good canidate to direct. 
It's now up to me to sift through the data and make three business recommendations based on that. 

Let's start off with these key questions:

### Dollars and Cents
* How much should we budget for production?
* How much can we expect to make domestically and globally?
* What can we expect for an average ROI?

### What? When? How Long?
* Which genres are most profitable?
* Which parental advisory ratings are most profitable?
* Which release months are most profitable?
* Which runtimes are most profitable?

### For Your Consideration... 
* Are more highly rated movies more profitable?
* What are some highly rated directors in the chosen genre?

## The Data

In the folder `Data` are movie datasets from:

* [IMDB](https://www.imdb.com/) - an invaluable source of information with ratings, titles, genres, director information, and more!
* [Rotten Tomatoes](https://www.rottentomatoes.com/) - (reviews, which gives us ratings for specific movies as well as written reviews (though we will only be focusing on the ratings themselves)
* [TheMovieDB](https://www.themoviedb.org/) - gives us release date, among other things
* [The Numbers](https://www.the-numbers.com/) -  a great source for the money behind the machine (production, domestic and worldwide gross)


## The Process

After reviewing all the files, I chose some specific files (and columns within those files) to combine, then followed the following process as needed:

* Creating dataframes from sqlite files that would play well with the other dataframes
* Capitalized and simplified titles of columns for easier reading and combining
* Converting date columns to just the month
* Converting string columns with currency to floats
* Resetting indexes
* Getting rid of outliers
* Dividing values of currency by a million for easier reading
* Dropping columns and pivoting my focus as issues and patterns were found

## Results

I focused on scatter plots and bar graphs with my reccommended budget labeled on each. While I have a few for each set of questions to consider, here are some examples: 

This is a scatter plot I used to demonstrate the average domestic gross compared to the production budget:

This bar graph shows the relationship of months movies were released and how much their grossed domestically on average:

In addition, this scatter plot shows the intruiging relationship between average rating and domestic gross, which will have us later when looking for looking for a director:

## Conclusions
* Expect to budget about 22 million dollars, and have an average return on investment of about 14.5 million dollars. Should you choose to go international, your potential  worldwide gross would be roughly 72.21 million dollars.
* Make an adventure film, rated G between 55-65 minutes, or 100-145 minutes, and release it in May or June. If you need to delay the release, (July and November for backup)
* Hire a director with international acclaim that has produced highly rated films, such as Richard Heap, as movies rated higher generally gross more and will do better on the worldwide stage.

## Next Steps

Looking more into the data in the future could help us hone in on some pretty specific aspects that could increase the profitability of our reccommendations for Microsoft:

* More consistent data and larger datasets could help give us a more accurate take on different aspects of our findings (specifically ratings)
* Looking into director info more closely would help pin down the aspects that could make for a more educated choice such as other work experience, age of films, money made from said films. This could also be applied to writers, editors, actors, and more.
* Understanding how marketing budgets can affect ROI, domestic gross, and foreign gross would be highly informative. 
* Comparing venues for showing the film (theatres, streaming, etc) would also help Microsoft see how markets were trending and what platforms would be more profitable. 



## Non-Technical Presentation
* [Here you will find my slideshow presentation](https://docs.google.com/presentation/d/1F7YMdGV7wwQWVfUvhbguNpTOeQabyAAIMdVyMaLj6SE/edit?usp=sharing)

## Repository Structure:
├── .canvas

├── .gitignore
├── LICENSE.md
├── README.md
├── Microsoft_Movie_Studio_Presentation.pdf
└── student.ipynb

