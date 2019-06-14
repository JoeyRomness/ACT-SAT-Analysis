# Project 1 SAT Participation Readme
> Joey Romness, June 14 2019, DSI-8


## Overview
> - For DSI project 1, we were asked to examine SAT and ACT datasets from 2017 and 2018 and, acting as if we were data scientists working for the college board, use the datasets to make inferences as to how money can best be spent if we are trying to increase SAT participation rates. The data sets were organized by state, showing each US state's percent participation as well as their average scores for every section of the ACT/SAT. With this data, I did an EDA and used visualization to display correlations between the different series data.

## Problem Statement
> ***In this analysis, we will be examining and comparing ACT and SAT data from across the United States so that we may infer and make recommendations for increasing SAT participation rates nationwide and in select states with low participation.*** 

## Executive Summary
- SAT participation nationwide is consistently lower then ACT participation nationwide. Because of this, we examined SAT and ACT data from the years 2017-2018 to try and find solutions to fix low SAT participation. After conducting an EDA and doing some data visualization, we inferred that ACT participation and SAT participation are negatively correlated. Because of this, it is likely that for the SAT to have more participation, it needs to compete with the ACT. Despite these results, our dataset may be unreliable because of our population size of 51. Our confidence interval is too high to concretely predict anything.  

## Data Dictionary
|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|ACT 2017, SAT 2017, ACT 2018, SAT 2018|The state in which the ACT and SAT results were gathered from.|
|act_2017_percent_participation|integer|ACT 2017|The 2017 ACT participation percentage in row's state|
|act_2017_english|float|ACT 2017|The average 2017 ACT english score in row's state|
|act_2017_math|float|ACT 2017|The average 2017 ACT math score in row's state|
|act_2017_reading|float|ACT 2017|The average 2017 ACT reading score in row's state|
|act_2017_science|float|ACT 2017|The average 2017 ACT science score in row's state|
|act_2017_composite|float|ACT 2017|The average 2017 ACT composite score in row's state|
|sat_2017_percent_participation|integer|SAT 2017|The 2017 SAT participation percentage in row's state|
|sat_2017_reading_writing|integer|SAT 2017|The average 2017 SAT reading and writing score in row's state|
|sat_2017_math|integer|SAT 2017|The average 2017 SAT math score in row's state|
|sat_2017_total|integer|SAT 2017|The average 2017 SAT total score in row's state|
|act_2018_percent_participation|integer|ACT 2018|The 2018 ACT participation percentage in row's state|
|act_2018_english|float|ACT 2018|The average 2018 ACT english score in row's state|
|act_2018_math|float|ACT 2018| The average 2018 ACT math score in row's state|
|act_2018_reading|float|ACT 2018|The average 2018 ACT reading score in row's state|
|act_2018_science|float|ACT 2018|The average 2018 ACT science score in row's state|
|act_2018_composite|float|ACT 2018| The average 2018 ACT composite score in row's state|
|sat_2018_percent_participation|integer|SAT 2018|The 2018 SAT participation percentage in row's state|
|sat_2018_reading_writing|integer|SAT 2018|The average 2018 SAT reading and writing score in row's state|
|sat_2018_math|integer|SAT 2018|The average 2018 SAT math score in row's state|
|sat_2018_total|integer|SAT 2018|The average 2018 SAT total score in row's state|

## Conclusions/Recommendations
- ***The SAT likely needs to compete with the ACT to increase its participation rates. For states where participation is very low like Arkansas, Alabama, and Mississippi, here are a few ways they could do this:*** 
 > - The college board could cooperate and negotiate with school districts so they pay for the SAT, not the students
 > - Promote free tools for improving SAT scores like Khan Academy
 > - Work with state governments to push for mandatory SAT participation
 > - Make changes to the SAT so it has more in common with the ACT

- ***Additional data desired:***
> - Having a larger population size would have been immensely helpful for data reliability and smaller confidence intervals. If we were working with County averages rather then State averages, perhaps our population size would not have been as much of a problem.
> - Having access to ACT/SAT datasets from 2016 and 2017 could have been helpful to see if participation rates were steadily increasing or decreasing. It is hard to discern whether or not something is growing between years if all we have access to is two years of data.

## Sources
- [https://www.orlandosentinel.com/news/education/os-ne-act-sat-florida-scores-20181024-story.html]
- [https://www.khanacademy.org/test-prep/sat] 





