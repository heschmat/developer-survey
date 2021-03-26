# Project: Write a Data Science Blog Post

## Overview
This is an analysis of the 2020 Stackoverflow developer survey. The survey includes about 60+K developers from 184 countries. My main motivation for this mini-project is to build a profile of a typical developer; more especifically I'll see how big a role _formal education_ plays in developers' career. 

Furthermore, I'll see into the factors that could make the job of a developer attractive, or less attractive. Most importantly, I'll investigate what programming languages and technologies less experienced developers or individuals interested in breaking into the field should focus on. I'll concolude the analysis by giving two pro-tips. 

For a short summary of the found results please refer to [my medium blog](https://hesch-mat.medium.com/halt-and-join-developers-community-9619e3cd3a62). 

## Understanding Data
This data set is based on a survey of 65,000 professional and aspiring software developers from 186 countries around the world, conducted by the [Stackoverlfow](https://stackoverflow.blog/2020/07/27/public-data-release-of-stack-overflows-2020-developer-survey/). Note: the survey was fielded in February 2020, so it does not reflect the aftermath of COVID-19.   

## Data Preparation
Mostly the data is clean. Some data cleaning is done because of the nature of the question that accepted multiple answers. One shortcoming of the data is that there are a lot of non-responders, sometimes as far as 1/3.    
However, since the purpose of the analysis is to conduct exploration no action is taken toward handling of missing values.  


## Results
1. Although overall majority of the developers believe formal education is an important requirement for their job, the result is not as strong amongst those developer who don't have a college degree; in fact, more than a 1/3 believe among them believe formal education is not important at all.   

2. Job satisfaction is all over the place, no clear picture here. But the results show that for more than 1/3 of them, working over time couple of days per month is totally normal. An interesting finding is that, 78% of the responders who identified themselves as _developer by profession_ also posited that they code for fun.    

3. Analysis of the professional development plans from developers shows that programming languags such as `javascript` and `python` are most in demand. Also `PostgreSQL` and `MongoDB` for structured and unstructured database are popular. Finally, frameworks such as `node.js` and `react.js` for web-development path, and `tensorflow` for machine learning and data science path seem to be marketable skills that everyone, especially those who want to advance their careers should pay attention to. Skills in relation to `DevOps` are viewed as important by majority of developers.   


## File Descriptions
`EDA.ipynb` is my exploratory data analysis in juypter notebook. 
`EDA.html` is the HTML format of the analysis for ease of view. 

## Libraries
- pandas
- matplotlib



## Acknowledgment
Kudos to Stackoverflow for [the survey data](https://stackoverflow.blog/2020/07/27/public-data-release-of-stack-overflows-2020-developer-survey/).
