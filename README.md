# Mars Webscraping
Module 11 Challenge

This project contained two parts. The first ask was to scrape titles and preview text from Mars news articles. The second ask was to scrape and analyze Mars weather data. The analysis for both parts is included below.


## Part 1: Mars News

I was asked to scrape titles and preview text from a Mars news articles site. Using the site <a href> https://static.bc-edx.com/data/web/mars_news/index.html</a>, I pulled a list of fifteen (15) titles and previews and compiled them in a json file. The first five titles and previews have been listed here.

ADD IMAGE OF JSON


## Part 2: Mars Weather Data

I was asked to scrape weather data from a Mars temperature data site. Using the site <a href> https://static.bc-edx.com/data/web/mars_facts/temperature.html</a>, I pulled a list of 1867 Martian Days data points and created a data frame of the information to analyze. The first five rows of data have been included in the image below.

ADD IMAGE OF data frame

As part of the analysis, I was asked to answer five questions. You can find the answers to those questions here.


### How many months exist on Mars?

Similar to Earth, there are <b> twelve (12) months on Mars</b>. The image below shows the number of rows in the data frame for each month.

ADD IMAGE OF months

### How many Martian (and not Earth) days worth of data exist in the scraped dataset?

There are 1,867 unique Martian days worth of data in the scraped dataset.

### What are the coldest and the warmest months on Mars (at the location of Curiosity)?

The <b> warmest month on Mars (at the Curiosity location) is Month 8</b> with an average minimum temperature of -68.382979 <sup>o</sup>C. Conversely, the <b> coldest month on Mars (at the Curiosity location) is Month 3</b> with an average minimum temperature of -83.307292 <sup>o</sup>C. The bar graph below shows the average minimum temperature by month from coldest to warmest.

ADD IMAGE OF temp_months

### Which months have the lowest and the highest atmospheric pressure on Mars?

The month with the <b> lowest atmospheric pressure on Mars (at the Curiosity location) is Month 6</b> with an average atmospheric pressure of 745.054422. Conversely, the month with the <b> highest atmospheric pressure on Mars (at the Curiosity location) is Month 9</b> with an average atmospheric pressure of 913.305970. The bar graph below shows the average atmospheric pressure by month from lowest to highest.

ADD IMAGE OF pressure_months

### About how many terrestrial (Earth) days exist in a Martian year?

There are approximately <b> 675 terrestrial (Earth) days in a Martian year</b>. To identify the number of Earth days, I graphed the minimum temperature from each day on a line graph, shown below, and looked at the approximate difference from one maximum to the next or one minimum to the next. To get 675, I calculated 1750 - 1075 because those are two easily identifiable minimums in the graph.

ADD IMAGE OF year


### Sources
