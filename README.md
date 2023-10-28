<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links




<br />
<div align="center">

  <h2 align="center"> How accurate are predictions for college football games? </h2>

  <p align="center">
    A deep dive into the world of Las Vegas predicting college football games over the last 5 years.
    <br />
  </p>
</div>



<!-- TABLE OF CONTENTS -->
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

Below is a link to my presentation slides and video where I have reported my findings in this project.

_[Presentation Slides](https://www.canva.com/design/DAFyOAern8k/ueN7V9QsyQEQEhL0gTomBg/view?utm_content=DAFyOAern8k&utm_campaign=designshare&utm_medium=link&utm_source=editor)_

I have also built a PowerBi dashboard to check out how well Las Vegas can predict your favorite team when they play at home and when they play away.

_[Dashboard](https://example.com)_

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

A.J. Grande - [@your_twitter](https://twitter.com/your_username) - email@example.com

Project Link: [https://github.com/your_username/repo_name](https://github.com/your_username/repo_name)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this space to list resources you find helpful and would like to give credit to. I've included a few of my favorites to kick things off!

* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)


<p align="right">(<a href="#readme-top">back to top</a>)</p>
