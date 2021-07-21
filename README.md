## Carbon Emissions Around the Globe

Project by:
* Sunny Kim
* McKenna DuVall
* Robert Gramlich
* Iram Pacheco Garcia


<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Data Visualization</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

For this project, we are going to analyze CO2 emissions data at the state level in the U.S. Additionally, we will analyze CO2 emissions and death by air pollution data on a global level by country to explore the relationship between CO2 emissions and air pollution related deaths. By incorporating the Google Weather and Geocode API, we hope to discover trends in climate change as it relates to carbon emission. 


### Research Questions:
* Is there a relationship between wealth distribution and co2 emissions in the U.S. by state (and globally by country)?
* Is there a relationship between co2 emissions and deaths caused by air pollution?
* What are top/bottom 5 carbon emitters in the U.S. and the globe?
* Is there a relationship between climate (highet montly temperature) and co2 emissions?

### Datasets and API’s:

* U.S. Energy Information Administration CO2 Emissions Dataset
* U.S. Energy Information Administration Median Income Dataset (U.S. States)
* World Population Review Median Income Dataset for Country
* [International Greenhouse Gas Emissions Data set](https://www.kaggle.com/unitednations/international-greenhouse-gas-emissions)
* [Death Due to Air Pollution dataset](https://www.kaggle.com/akshat0giri/death-due-to-air-pollution-19902017)


### Built With

* Jupyter Notebook
* pandas
* numpy
* scipy
* matplotlib
* gmaps
* requests



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/sunwoo-kim20/global-climate-change-analysis.git
   ```
2. Install
   ```sh
   !pip install matplotlib
   !pip install pandas
   !pip install numpy
   !pip install requests
   !pip install json
   !pip install gmaps
   !pip install os
   !pip install scipy
   ```
3. Create Google API key and add to a config.py file
   ```sh
   g_key = "YOUR KEY"
   ```



## Data Visualization
### CO2 Emissions of BRIC Countries from 1990-2017
![CO2 Emissions of BRIC Countries from 1990-2017](https://github.com/sunwoo-kim20/global-climate-change-analysis/blob/main/output-data/images/bric-co2-display.png)

### GDP vs CO2 Emissions Regression
![GDP vs CO2 Emissions Regression](https://github.com/sunwoo-kim20/global-climate-change-analysis/blob/main/output-data/images/gdp-co2-display.png)

### CO2 Emissions vs Climate Regression for China
![CO2 Emissions vs Climate Regression for China](https://github.com/sunwoo-kim20/global-climate-change-analysis/blob/main/output-data/images/china-regression-display.png)




<!-- CONTACT -->
## Contact

Sunny Kim - s.kim32415@gmail.com

Project Link: [https://github.com/sunwoo-kim20/global-climate-change-analysis](https://github.com/sunwoo-kim20/global-climate-change-analysis)



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/github_username/repo.svg?style=for-the-badge
[contributors-url]: https://github.com/github_username/repo/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/github_username/repo.svg?style=for-the-badge
[forks-url]: https://github.com/github_username/repo/network/members
[stars-shield]: https://img.shields.io/github/stars/github_username/repo.svg?style=for-the-badge
[stars-url]: https://github.com/github_username/repo/stargazers
[issues-shield]: https://img.shields.io/github/issues/github_username/repo.svg?style=for-the-badge
[issues-url]: https://github.com/github_username/repo/issues
[license-shield]: https://img.shields.io/github/license/github_username/repo.svg?style=for-the-badge
[license-url]: https://github.com/github_username/repo/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/github_username

