# console-finances
Assignment 4 of the Front-End Web Dev bootcamp to analyze financial records of a company


****
<a name="readme-top"></a>

<!-- PROJECT LOGO -->
<br />
<div align="center">
<!-- Webpage icon -->
  <a href="https://icollier77.github.io/console-finances/" target="_blank">
    <img src="./assets/calc-icon.jpg" alt="Logo" width="80" height="80">
  </a>

<h1 align="center">Financial Calculator</h1>

  <p align="center"> This is a mini application built in JavaScript to analyze financial records of a company.</p>
    <!-- links to deployment -->
    <a href="https://icollier77.github.io/console-finances/" target="_blank">Financial Calculator</a>
    ·
    <a href="https://github.com/icollier77/console-finances" target="_blank">GitHub repo</a>
    ·
  <br>
  <br>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#project-goal">Project Goal</a></li>
        <li><a href="#project-specifications">Project Specifications</a></li>
        <li><a href="#sample-result">Sample Result</a></li>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li><a href="#development">Development</a></li>
    <li><a href="#deployed-project">Deployed Project</a></li>
      <ul>
        <li><a href="#deployed-application">Deployed Application</a></li>
        <li><a href="#links-to-deployed-project">Links to Deployed Project</a></li>
      </ul>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## `About The Project`

### `Project Goal`
The goal of this project is practice basic JavaScript skills by building a financial console to analyze financial records of a company.

### `Project Specifications`

<p>The application should calculate the following:</p>
<ol>
  <li>The total number of months included in the dataset.</li>
  <li>The net total amount of Profit/Losses over the entire period.</li>
  <li>The average of the **changes** in Profit/Losses over the entire period.</li>
  <li>The greatest increase in Profit/Losses (date and amount) over the entire period.</li>
  <li>The greatest decrease in Profit/Losses (date and amount) over the entire period.</li>
  <li>The final code should print the analysis to the console.</li>
</ol>
</p>

### `Sample Result`

<p>The resulting analysis should look similar to the following:

![sample result][sample-img]
</p>


### `Built With`

I used the following technologies when building this application: 
* [HTML][html-url]
* [JavaScript][js-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- The build process -->
## `Development`

Overall the process was very enjoyable. Taking those couple of weeks of [CS50x][cs50-url] finally paid off as I was very comfortable with the logic. I still had to look up a couple of things (such as how to _create an array from a array_, or how to calculate _min_, _max_, _average_ in JavaScript). 

I also went an extra mile and used `Intl.NumberFormat('en-US').format()` to present the numbers in a more readable format.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- Deployed project -->
## `Deployed project`

The project is now live.

### `Deployed application`

The deployed page looks like this:

![Deployed page][deployed-img]


### `Links to deployed project`

You can find the current portfolio webpage, its corresponding code, and the previous portfolio webpage here:

- [ ] [Financial calculator][deployed-url]
- [ ] [Project repo][repo-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



Credit:

Financial Calculator Icon: https://www.freepixel.com/images/free-icons-financial-calculator-icon-in-green-and-orange-color-11063127


<!-- MARKDOWN LINKS & IMAGES -->
[deployed-img]: ./assets/fin-calc.png
[deployed-url]: https://icollier77.github.io/console-finances/ 
[repo-url]: https://github.com/icollier77/console-finances
[sample-img]: ./assets/sample-result.png
[html-url]: https://www.w3schools.com/html/
[js-url]: https://www.w3schools.com/js/default.asp
[cs50-url]: https://www.edx.org/learn/computer-science/harvard-university-cs50-s-introduction-to-computer-science?utm_source=google&utm_campaign=19339199037&utm_medium=cpc&utm_term=edx%20cs50%20certificate&hsa_acc=7245054034&hsa_cam=19339199037&hsa_grp=145482383900&hsa_ad=642397268542&hsa_src=g&hsa_tgt=kwd-943661133775&hsa_kw=edx%20cs50%20certificate&hsa_mt=e&hsa_net=adwords&hsa_ver=3&gad_source=1&gclid=CjwKCAiA98WrBhAYEiwA2WvhOjuSuvwvTR6Roh_ofBCdigAjuXu1cveTglwj0XsVvcO94UOTb6X0cRoCj-YQAvD_BwE