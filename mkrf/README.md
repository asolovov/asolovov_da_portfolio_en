# [Russian film distribution data analysis](https://github.com/asolovov/asolovov_da_portfolio_en/blob/main/mkrf/mkrf_en.ipynb)

### The purpose of the reserch:
It is necessary to study the Russian film distribution market and identify current trends. Pay attention to the films that have received government support. Try to answer the question of how interesting such films are to the viewer.

### Tools:

- Pandas
- Pyplot

### Reserch Plan:

- 1 Introduction to data
- 2 Data preprocessing
- 3 Exploratory data analysis
  - 3.1 Number of films and data quality
  - 3.2 Rental dynamics by years
  - 3.3 Box office average and median by years
  - 3.4 Study of the age restrictions influence
- 4 Films that received government support
  - 4.1 Additional data processing
  - 4.2 Exploratory analysis
- 5 Research results

### Summary:

**Important information:**

Apparently, the data before 2014 is corrupted. Only 25% of films have full release information versus 50% for films after 2014. Also, apparently, different methods were used to take into account the fees, until 2014, the fees were indicated in thousands, after that in numbers. Most of the analysis is based on data from 2015 to 2019

**Study of the entire sample:**

Most rental certificates were issued in 2010, the least in 2017
The economic efficiency of rolled products can be graded as follows:
- 1st place 2017
- 2nd place 2018
- 3rd place 2016 and 2019
- 4th place 2015

**Study of supported films:**

Only 2017 and 2018 showed a profit, the rest were unprofitable. Total profit result for the entire period, is close to zero, profitability below 1%.
The average film rating is kept at the level of 6 out of 10 for the entire period. Most films were supported in 2015, the same year there is the largest loss, the least in 2017 and the same year there is the largest profit.
