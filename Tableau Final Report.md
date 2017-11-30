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

**Story Line**

<p align="center">
  <img width="860" height="600" src="https://github.com/HuipingZhu/Tableau-Final-Project/blob/master/1.png">
</p>

<p align="center">
  <img width="860" height="600" src="https://github.com/HuipingZhu/Tableau-Final-Project/blob/master/2.png">
</p>


After we had a general overview of this dataset regarding to profit, we thought it was more meaningful to figure out the most profitable and popular movie genre, director and actor. Therefore, we grouped our dataset into three different subsets in which budget is low, medium and high. Therefore, we can use filters to dynamically show the most profitable actresses, directors, and movie type by different budget levels.

To make a profitable and high-IMDB score movie, we need to consider the following five aspects: genre, director, actor, budget and country. And we take the data from year 1990 to year 2016 to do our analysis.



<p align="center">
  <img width="460" height="300" src="http://www.fillmurray.com/460/300">
</p>



filtered actor 1,2,3 based on profitability to get the top 30

**Challenges**

We encountered difficulty when we found that the dataset we selected for our models has missing data and missing attributes such as profit and profitability. We put into considerable time and effort to think about how to wrangle the data and to extract useful information. We found a way to calculate the profit (gross minus budget). We also cleaned  up and built an accurate dataset. Moreover, some attributes in the dataset has multiple value for one cell such as Genre. So we split it into two new columns: genre-main type and genres-others.  In addition, we only have facebook likes data to measure the popularity of movies, which may affect our model accuracy and robustness during our predictive analytics process. Another challenge was we would like to find new perspectives to conduct the analysis since it’s a very common dataset. It took us lots of time for online searches and to have our tableau functioning properly.

For reference, there is the link for [Tableau workbook online](https://us-east-1.online.tableau.com/#/site/huiping/workbooks/189842/views).


<p align="center">
  <b>Some Links:</b><br>
  <a href="#">Link 1</a> |
  <a href="#">Link 2</a> |
  <a href="#">Link 3</a>
  <br><br>
  <img src="http://s.4cdn.org/image/title/105.gif">
</p>



<p align="center">
  <img width="460" height="300" src="http://www.fillmurray.com/460/300">
</p>




### Genre
This is a graph showing the average profit trend of top 10 genres (genres-main type) with the high average profitability. 
### Country
Next, we used geographic data to plot the profitability of movies by country.




Finally, we used correlation analysis to identify relationships between different continuous variables. We identified that a movie’s gross revenue has a strong positive relationship with Facebook likes.



![Alt Text](https://github.com/HuipingZhu/Tableau-Final-Project/blob/master/screenshot.png)

`<addr>` element here instead.

**quote type:**
> the present is our past.

**quoting code:**
`git status`

**links:**
This site was built using [GitHub Pages](https://pages.github.com/).

*This text will be italic*

**This text will be bold**


- George Washington
- John Adams
- Thomas Jefferson


1. James Madison
2. James Monroe

