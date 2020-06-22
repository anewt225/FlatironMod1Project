# Microsoft Movies

#### A Market Entry Proposal

### Overview
Tasked with the project of finding and analyzing data to guide Microsoft's potential entry into the Movie Industry, this project seeks to provide one way in which Microsoft might analyze limited data to commence this entrance. Analyzing the runtime and production budget of highly rated movies provided recommendations for Microsoft in terms of how long an ideal movie would be, and how much to set aside for the prodcution budget.

***

### Repository Navigation
Data
Visualizations
Presentation
Notebook

### ReadMe Navigation

1. [Business Understanding](#Business-Understanding)
2. [Data Understanding](#Data-Understanding)
3. [Analysis and Visualizations](#Analysis-and-Visualizations)
4. [Conclusion](#Conclusion)
5. [Recommendations for the Future](#Recommendations-for-the-Future)
6. [Project Info](#Project-Info)

***

## Business Understanding

Given the project proposed by Microsoft, dozens of questions were drafted in the brainstorming process related to scope, accuracy, deliviery, consumer, content, and cost. This specific analysis was narrowed down to content and cost questions, specifically:

1. What budget range should Microsoft expect to set for a highly rated movie?

2. What runtime length range should Microsoft expect to set for a highly rated movie?

## Data Understanding
The data used for this project was provided by Flatiron school and included several datasets from IMDB, BOM, Rotten Tomatoes, The Numbers, and the Movie Database. From among the datasets provided, only 3 were used to narrow the scope of analysis. 

Focusing on budget data and rating data from IMDB, we used three datasets: "IMDB Title Basics", "IMDB Title Ratings", and "TN Movie Budgets". Within those datasets, we focused on these specific items:

1. Movie Title
2. Runtime in Minutes
3. Ratings
4. Budget

## Analysis and Visualizations

I started with several visualizations to gain a general sense of what the data demonstrated:

![AverageRating%20vs%20NumVotes.png](attachment:AverageRating%20vs%20NumVotes.png)


This first visualization allowed us to narrow down our analysis to movies with an average rating of 7 or higher. 

Seaborn in python required cleaner data in order to generate effective visualizations, so I created bins of average ratings at intervals of .5, and then produced overall visualizations of the data to see if we could glean any information from them:

![HighestRated%20pairplot.png](attachment:HighestRated%20pairplot.png)

After a touch more cleanup, I noticed more trends in the data which drew me back to the analysis of the business questions: optimal runtime and optimal budget based on ratings. Using boxplots was the most effective way to demonstrate range:

![Runtime%20Range%20vs%20Ratings%20Visualization.png](attachment:Runtime%20Range%20vs%20Ratings%20Visualization.png)



![Budget%20Range%20vs%20Ratings%20Visualization.png](attachment:Budget%20Range%20vs%20Ratings%20Visualization.png)

I initially anticipated this to be a quick, one number recommendation. However, analyzing these two visualizations showed patterns by certain groupings. Given the data left out and the myriad caveats along the way, I decided to provide the Microsoft decision making team with more flexibility by providing them with options.


## Conclusion
Based on the images above, I made the following recommendations to Microsoft:

1. **"Good Enough"** (ratings between 7-8)
    1. Runtime: 100 - 125 Minutes
    2. Budget: &#0036 10 - &#0036 50 million
    
2. **"Just Right"** (ratings between 8-8.5)
    1. Runtime: 110 - 150 Minutes
    2. Budget: &#0036 25 - &#0036 100 million
    
3. **"Go for Gold"** (ratings between 8.5-9)
    1. Runtime: 140 - 160 Minutes
    2. Budget: &#0036 100 - &#0036 150 million
    

## Recommendations for the Future



#### Data Recommendations
Within the data given, I recommend doing further research into the following:

1. Data scope - every step of narrowing down for cleaner data has an impact on our analysis outcomes.

2. Nuance in data - there's something more behind the number of votes when compared to the higher rating that could warrant further explanation.

3. Quality control through multiple sources - more of the given data should be analyzed for a more complete picture, e.g., using Rotten Tomatoes ratings in addition to IMDB ratings.

4. Data accuracy - more up-to-date data analyzing current box office income and projections given Covid19 and physical distancing measures' impact upon our data points.

#### Project Recommendations
In terms of the project itself, I recommend Microsoft do further research on the following:

1. Content & Delivery - e.g, genre? platform? app?
2. Competition - e.g., Netflix, HBO
3. Competitive Advantages - e.g. Xbox, Office
4. Threats - e.g., pandemics, protests

***

## Project Info

Contributor: __[Alexander Newton](https://www.linkedin.com/in/anewt/)__

Languages  : Python

Tools/IDE  : Powershell (Windows), Anaconda, Jupyter Notebook, Google Slides

Libraries  : numpy, pandas, matplotlib, seaborn

Duration   : June 2020
Last Update: 06.22.2020


```python

```
