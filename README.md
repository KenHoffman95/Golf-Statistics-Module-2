# Golf-Statistics-Module-2

## Introduction

For this project, I analyzed data and metrics regarding PGA golfers. I reviewed data for 1678 golfers (over 9 seasons from 2010-2018) in order to determine which stats and metrics play the biggest role in determining a PGA golfers' earnings per Tournament. In order to get the data collection of PGA golfers to review, I downloaded a dataset from Kaggle that was webscraped from PGA.com and uploaded by Brad Klassen. I created data visualizations through MatPlotLib, Seaborn and Pandas in order to analyze the data. For further analysis, I used Statsmodels to create multiple linear regression models. 

## Objectives

Using the data that I collected, I wanted to answer the following questions:
* What does a distribution of golfers' earnings per tournament look like at a 95% confidence interval?
* Which golfers make the most and least amount of money per tournament?
* Does driving distance affect a golfers' earnings per tournament?
* Does driving accuracy affect a golfers' earnings per tournament?
* Does percentage of Greens in Regulation affect a golfers' earnings per tournament?
* Does the average number of putts per round affect a golfers' earnings per tournament?
* Can one make an accurate multiple linear regression model using golf stats and metrics to predict earnings per tournament?

## Presentation

https://docs.google.com/presentation/d/1sqSAk0G6kh9t0Rz0cYvwV1hqxA3zGEdJ7IKTSmBsY1Y/edit?usp=sharing 

## Conclusions

Using the data that I collected, I was able to draw the following conclusions:
* The mean earnings per tournament for PGA golfers is $60,940.95 with a 95% confidence interval of $57,982.81 to $63,899.09
* From performing two-sample t tests I was able to determine:
  * Longer drivers make more money per tournament than shorter drivers
  * Accurate drivers do not make more money per tournament than inaccurate drivers
  * "Good" putters, that average less than 29.14 putts per round, make more money per tournament than "bad" putters
  * Golfers with a high GIR% make more money per tournament than golfers with a lower GIR%
* Since there is a lot of variability in the purse and payout breakdown per PGA Tournament, it is a lot easier to predict a PGA golfers’ scoring average based on metrics than it is to predict their average earnings per tournament



