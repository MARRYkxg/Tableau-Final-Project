<p align="center">
  <b> </b><br>
<p align="center">
  <b>  </b><br>
<p align="center">
  <b>  </b><br>
<p align="center">
  <b>Business Analysis Skills Workshop  --Tableau Final deliverable</b><br>
<p align="center">
  <b>Team 10</b><br>
<p align="center">
  <b>Jie Min, Justin Soniat, Huiting Tang, Huiping Zhu</b><br>
<p align="center">
  <b>December 1, 2017 </b><br>
<p align="center">
  <b> </b><br>
<p align="center">
  <b>  </b><br>
<p align="center">
  <b>  </b><br>

**Executive Summary**

Movies are a very common form of entertainment worldwide where people spend a significant amount of their leisure time. The movie industry is worth a lot and currently experiencing an exciting period of change because data analytics provides an opportunity for movie companies to more accurately predict the success of future movie releases. 

In this project, we are going to analyze the possible factors affecting movies’ profitability and popularity. Based on the analysis results, we will make suggestions to movie producers on how to define movie types, directors, and actors or actresses so that they could create movies that are both profitable and popular.

To do the analysis, we selected the IMDB 5000 Movie Dataset because it provides a well-constructed source of data with variables such as financial information, directors, actors and movie genre, which we expect to be correlated with box office success. The dataset also provides a sample size of greater than 5,000 movies that we expect will provide statistical significance for increasing revenue and reducing uncertainty with producing new movies. The data provided in this dataset sheds light on customer’s choices and the feedback helps target the right audience, optimize marketing strategies and customer’s taste, and predict whether a movie will be popular before it is produced.

<p align="center">
  <b> </b><br>
 
**Story Line**

Workflow of Project

<p align="center">
  <img width="950" height="270" src="https://github.com/HuipingZhu/Tableau-Final-Project/blob/master/workflow.png">
</p>


<p align="center">
  <b> </b><br>

Steps of Data Analysis

- We found data in the IMDB dataset each cell in genre contains multiple movie type information. So, we split the genre column into “genres-main type” column with only the first genre of the movie and “genres-others”, which contains the rest part of the genre.
- First, we were interested in finding what types of movies to recommend to movie producers. So we count the records for each genre and sort them, and we found that animation, comedy, action, and drama are popular and profitable movie genres. Then, since our dataset include data over 100 years, we only want to see the recent trend of profitability for each genre. So we picked out data from 2000 to 2016 and made line charts of average profit for each genre over year. We found that Animation movies show the most profitability along with a recent upward trend, but this genre is also susceptible to volatility. The success or failure of blockbuster releases likely plays a role in this volatility.
- Secondly, we took budget into consideration. We set high, medium, and low budgets and made bar charts to see the profitability for each genre under different budget categories. We found that high budget films present a high risk for movie-producers, so movie producers do not necessarily need to invest a significant amount of money to make a profitable movie.
- Thirdly, we mapped the gross, budget and profit of movies around the world and we also found that this idea holds true across the international movie-making industry. 
- We further want to figure out which director should be chosen for certain genres we decided previously. Here, we consider profit, facebook likes and IMDB score to find the directors that can help produce both highly popular, profitable and highly rated movies.
- After decide directors, we use the similar method to figure out which actors should be chose including the first leading actor/actress, the second and the third one. We also found that the second leading actor may provide the most value for producers to choose an actor or actress with a household name for this type of position rather than as the leading actor or actress.


Business Summary

Our final recommendation states that producers should create an animated film to increase their chances of developing a profitable movie. If the producer does not have the resources to create an animated film, the producer can still use the same strategy of selecting well-known actors and actresses for supporting roles or cameo appearances in order to create a film that earns a high amount of revenue without implementing too costly of a cast. Additionally, when choosing directors, movie producers should focus more on their previous average movie profitability rather than their popularity. 

There is the link of [Tableau public](https://public.tableau.com/profile/huiping.zhu#!/vizhome/BAWorkshopFinalProject-IMDBMovieDataAnalysis_0/IMDBMovieDataAnalysis?publish=yes).



<p align="center">
  <b> </b><br>

**Challenges**

We encountered difficulty when we found that the dataset we selected for our models has missing data and missing attributes such as profit and profitability. We put into considerable time and effort to think about how to wrangle the data and to extract useful information. We found a way to calculate the profit (gross minus budget). We also cleaned  up and built an accurate dataset. Moreover, some attributes in the dataset has multiple value for one cell such as Genre. So we split it into two new columns: genre-main type and genres-others.  In addition, we only have facebook likes data to measure the popularity of movies, which may affect our model accuracy and robustness during our predictive analytics process. Another challenge was we would like to find new perspectives to conduct the analysis since it’s a very common dataset. It took us lots of time for online searches and to have our tableau functioning properly.
