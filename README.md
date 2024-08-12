# Mars Webscraping
Module 11 Challenge

This project contained two parts. The first ask was to scrape titles and preview text from Mars news articles. The second ask was to scrape and analyze Mars weather data. The analysis for both parts is included below.


## Part 1: Mars News

I was asked to scrape titles and preview text from a Mars news articles site. Using the site <a href> https://static.bc-edx.com/data/web/mars_news/index.html </a>, I pulled a list of fifteen (15) titles and previews and compiled them in a json file. The first five titles and previews have been listed here.

ADD IMAGE OF JSON


## Part 2: Mars Weather Data

I was asked to scrape weather data from a Mars temperature data site. Using the site <a href> https://static.bc-edx.com/data/web/mars_facts/temperature.html </a>, I pulled a list of 1867 Martian Days data points and created a data frame of the information to analyze. The first five rows of data have been included in the image below.

ADD IMAGE OF data frame

As part of the analysis, I was asked to answer five questions. You can find the answers to those questions here.


### How many months exist on Mars?

Similar to Earth, there are twelve (12) months on Mars. The image below shows the number of rows in the data frame for each month.

ADD IMAGE OF months

### How many Martian (and not Earth) days worth of data exist in the scraped dataset?

There are 1,867 unique Martian days worth of data in the scraped dataset.

### What are the coldest and the warmest months on Mars (at the location of Curiosity)?

The warmest month on Mars (using Curiosity) is Month 8 with an average minimum temperature of -68.382979 <sup>o</sup>C

ADD IMAGE OF temp_months
