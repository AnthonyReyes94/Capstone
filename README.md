## Draft Dreams to Court Realities 

## Table of Contents 

* [Summary](#summary)
* [Motivation](#motivation)
* [Data Question](#data-question)
* [Tech](#tech-used)
* [Data Sources](#data-sources)
* [Issues](#issues)
* [Conclusion](#conclusion)

## Summary 

This project aims to analyze college basketball performance metrics to identify key factors that contribute to success for NBA draft prospects. Motivated by the growing importance of data analytics in sports decision-making, my goal is to uncover any trends that translate college performance into NBA success. By leveraging my data from college and NBA sources, I’ll explore metrics such as years in college, draft position, player attributes, and on-court statistics for collegiate and professional careers. I will be analyzing all NBA players who began their professional career in 2014 or later, as this began the rise of the 3-point shot and offensive explosion. 

## Motivation

With March Madness occurring at the time of this proposal, I have often thought about what makes an NBA draft prospect successful in the NBA. There are a variety of factors that could potentially affect a college player’s pro-career trajectory: experience (one-and-done or senior), college, conference, domestic or international, draft position, position-played, and a variety of others. Not to mention, in the last decade, the NBA has pivoted towards an offensive-dominant and analytically driven league, which could drastically affect which players are drafted. Because there are so many factors to analyze, there have been many General Managers who have completely “whiffed” on lottery draft picks, but, also, some General Mangers have hit the “lottery” in later rounds. I want to be able to find trends from the past that can make the NBA Draft Day a lottery for more GMs. 

## Data Question
The overarching question I want to focus my research and analysis upon is:  
* “What college measurables translate to having a successful NBA career?” 

I will go about the process of determining what college measurables are transferrable to the NBA by going through a 5-step analysis. 

* Performance - This step involves analyzing various performance metrics of college basketball players including: 
  * Points 
  * Rebounds
  * Assists
  * Blocks
  * Steals
  * Turnovers
  * FG%
  * PER (Player Efficiency Rating) 
  * Win Shares

I aim to take these college metrics and analyze their relationship with the same NBA performance metrics. 

* Physique – Through this step, I aim to determine if physical characteristics are conducive to success at the professional level. By examining correlations and NBA performance metrics, I will be able to provide valuable insights into the role of physicality in basketball success. 

* Pick – During this phase of the analysis, I will be gaining insight into how/if draft position is an effective measure of NBA success. 

* Position – This step will involve a by-position analysis to determine which college positions have the greatest impact on the professional game.   

* Place – The college or university a player attends can shape their development, exposure, and opportunities in the basketball world. Different school have different coaching philosophies, playing styles, competition levels, and resources that can impact player performance and readiness for the NBA. By examining the schools attended by NBA players and their subsequent professional success, I aim to identify key factors that provide a seamless transition to the NBA. 


## Tech Used
Python: Webscraping, cleaning data, and to make csv files 

Tableau: Various aggregations and visualization/presentation construction

## Data Sources

https://www.sports-reference.com/cbb/
https://www.basketball-reference.com/
https://public.opendatasoft.com/explore/dataset/us-colleges-and-universities/table/?flg=en-us

## Issues
Known Issues and Challenges

* Based on my data sources, I needed to webscrape the data in order to use it for this capstone. Ran into many issues with network erros and bot detection
* Differences in minutes being played in NBA and College which might skew the “per game” data (based all stats on a “per minute” basis) 
* Players with the same name
* Dealing with data that was being updated daily

## Conclusion

Based on the findings of this analysis, it is believed that adhering to the following guidelines during the drafting process will lead to a smoother transition from college to the NBA.
* The ability to effectively shoot from 3PT range
* Able to gather rebounds and generate blocks
* Possess playmaking abilities, specifically assists 
* Opt for players who have higher WS per Game and PER 
* Height of at least 6 feet and 6.5 inches and weigh at least 215 lbs
* If your team is in a position for a lottery pick (top 10 pick), don’t trade down because those are where the players with the highest PERs can be found. 
* Find players who have position versatility (F-G) who have the size to play near the rim as a Forward but also possess ball-handling skills and can hit shots from beyond the arc as a Guard 
* College team doesn’t play much of a factor in NBA performance metrics


