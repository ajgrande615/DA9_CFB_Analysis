<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>

<br />
<div align="center">

  <h1 align="center"> How well can College Football Games be Predicted? </h2>

  <p align="center">
    A deep dive into the world of Las Vegas predicting college football games over the last 5 years.
    <br />
  </p>
</div>



<!-- TABLE OF CONTENTS -->
## Table Of Contents
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#process">Process</a></li>
    <li><a href="#deliverables">Deliverables</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

College football is one of the greatest sports in the world. Every Saturday in the fall, there are hundreds of games all across the country featuring some of the best (and worst) football there is to offer. With the rise in popularity of sports gambling, there is more and more talk about how Las Vegas casinos predict the outcomes of these games.

They do this by setting the "spread", which is the expected difference in the final score between the two teams. 

It is most easily explained with an example:
* Team A is favored to win against Team B by more than 4 points or more.
* Team A's spread for the game would be -3.5 points, meaning their margin of victory must be 4 or more to cover their spread.
* Team B's spread for the game would be +3.5 points, meaning their score must lose by less than 3 points or win the game to cover their spread.
* For this example, let's say that Team A won the game by 2 points. Because their margin of victory does not cover the -3.5 spread set for them, the winning bet would be those who chose Team B +3.5 because they lost by less than 3.5.

With that in mind, here is why it interests me and why I want to learn more:
* Though it is used for casinos to make money on sports betting, it is also a fascinating way to predict the outcomes of these college football games. 
* The casinos setting these lines (and those that bet these games regularly) have to be doing tons of research on these games. How accurately can they actually predict the outcomes?
* Are there teams or conferences they can or cannot predict accurately on a regular basis?

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- Process -->
## Process

The first set was to find a data source, which came in the form of [collegefootballdata.com](https://collegefootballdata.com/).

Founded and maintained by a fellow college football fanatic and data lover, it is an incredible resource that is kept up to date and made easy to access via their Python API, which I utilized for this project.

From there, my goal was to aggregate the data into one data frame so I could compare the last 5 years' worth of data all at once. This included creating columns with for loops to give me columns I could compare across the dataframe and start finding trends.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- Deliverables -->
## Deliverables

The PowerPoint above is my presentation that goes through the whole project.
I have also built a PowerBi dashboard to check out how well Las Vegas can predict your favorite team when they play at home and when they play away.
That is also in the PowerPoint embedded towards the end.


<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

A.J. Grande - [LinkedIn](https://www.linkedin.com/in/ajgrande615/)

[Project Link](https://github.com/ajgrande615/DA9_CFB_Analysis)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

I want to shout out some of the resources that helped me through this project:

* Special thanks to Nashville Software School, especially the instructors of Data Analytics Part-Time Cohort 9.
* My DA9 classmates, I really enjoyed walking through this with you and helping each other along the way
* [collegefootballdata.com](https://collegefootballdata.com/) for being a great resource to find all the data I needed to do this analysis.


<p align="right">(<a href="#readme-top">back to top</a>)</p>
