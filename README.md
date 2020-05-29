# DS051120-Mod1-Project-Brad-Kenny
# Module 1 Final Project

## Brad Ellisor and Kenny Oh

## Introduction

At the end of Module 1 of Flatiron School's Data Science program, we were tasked with completing a Final Project demonstrating the skills we learned throughout our first three weeks. This project encapulates skills including:

* Python
* Webscraping
* API Calls
* Python Libraries: Pandas, Numpy, Matplotlib, and Seaborn
* Data Cleaning
* Data Visualization

## The Project

Microsoft sees all the big companies creating original video content, and they want to get in on the fun. They have decided to create a new movie studio, but the problem is they don’t know anything about creating movies. They have hired you to help them better understand the movie industry.
Your team is charged with doing data analysis and creating a presentation that explores what type of content is currently doing the best at the box office. You must then translate those findings into actionable insights that the CEO can use when deciding what type of content they should be creating.

## Project Checklist:

- Pull data from at least 2/3 sources (1 data source per team member)
- Develop a pipeline for your data, from API/scraping to dataframe. Save down your clean data as .csv(s)
- Generate descriptive statistics to compare the success of different content 
- A slideshow presentation that entails the following:
- The purpose of your analysis and why it matters
- 4 well labeled visualizations created using Matplotlib/Seaborn
- 2 meaningful summary tables (do not copy and paste results from Pandas)
- Give at least two actionable insights (What type of content should they be looking to
produce? What should the budget requirements be? Should they recruit certain actors for their content?)

## Posted to git repo:
- README.me
- Python files and Jupyter notebooks with clean and commented code
* api_final, 
* scraping_final,
* and analysis_final
- A link to our Google slide show



## Objectives

Our objectives for the project:

* Collect Data using webscraping and API calls and clean it in order to analyze the Data.
* Create visualizations from the data in order to come up with a recommendation.
* Use the insight and Visualizations from our data to present clear and concise recommendations.
* Timely completion of deliverables

# Questions 
Questions we asked:

* Do ratings have an impact on Gross Revenue?
* What Actors have "Star Power"?
* How is movie revenue impacted by time?
* What Genres have the highest mean revenue?
* What Genres have the highest mean revenue in the last decade?
* Highest grossing directors in the last decade?
* Highest ROI directors in the last decade?f the film?

# The Dataset
We used a combination of webscraping and API calls for our project. 

Webscraping
* Box Office Mojo

API
 * TheMovieDB.org
 * OMDB

Once we collected the data, our initial results were for 10,000 movies. After scrubbing our data, we used 4,058 movies.

# Our Recommendations

## Microsoft should makes films in the action and adventure genre.
The highest grossing genres both historically and within the last decade have been in the animation, action, adventure genres. While animation can be subjected to over saturation. Action and adventure films are a solid genre to break into.

## Microsoft should hire 'A-List' actors top directors.
While the budget would inevitably increase. From the Data, it is likely that a higher budget movie made by quality directors and known actors will experience longterm success.

# Conclusion

Upon reviewing of our analysis, we determined that Microsoft should create a movie saga based on Halo Franchise for the following reasons.

## 1. Ratings have a weak relationship with Average Gross Revenue.
There is a very weak relationship between Ratings and Average Gross Revenue. This means that just because a movie is positively rated doesnt necessarily indicate it will be profitable. 
![Fig1](/IMAGES/1_Rating_V_Gross.png)
![Fig2](/IMAGES/2_Corr_HM.png)





## 2. Movie Revenue v Budget by Years
![Fig4](/IMAGES/3-5_ MovieRevenuevBudgetbyYears.png)



## Genre
We wanted to find out what the popular genres in the movie industry are today. By comparing the descriptive statistics of each of the genres, plotted over Average Gross Revenue, we were able to see that the three franchises with the highest gross were Action, Adventure, and Animation.
![Fig6](/IMAGES/5_GenreAnalysis.png)

![Fig7](/IMAGES/6_Genrelast10.png)






## 3. Hiring accomplished Actors and Directors has a positive trend on Gross Income.
While the relationship between big name actors, top directors and high grossing films might seem commensense, we present statistical evidence that demonstrates there is a positive relationship between the two. 


![Fig5](/IMAGES/4_Top25Actors.png)

![Fig8](/IMAGES/7_DirGross.png)

![Fig9](/IMAGES/8_DirROI.png)


# Next Steps

* Look at Budget per genre
* Duration of movies compared to Adj. Lifetime Gross
* Compare creating your own films to leasing existing IP out 
* Success rate of sequels
