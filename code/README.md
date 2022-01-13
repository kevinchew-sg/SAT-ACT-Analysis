# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Standardized Test Analysis

### Problem Statement

This project seeks to understand the trends behind SAT Participation Rate and SAT Score. More specifically, does an increase in SAT Participation Rate lead to an increase in SAT Score? 

### Data Sources Used
 
* [`sat_2018.csv`](./data/sat_2018.csv): 2018 SAT Scores by State ([source](https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/))
* [`sat_2019.csv`](./data/sat_2019.csv): 2019 SAT Scores by State ([source](https://blog.prepscholar.com/average-sat-scores-by-state-most-recent))
* [`us_median_household_income_2019.csv`](./data/us_median_household_income_2019.csv): Median Household Income by State ([source](https://data.census.gov/cedsci/map?q=S1901%3A%20INCOME%20IN%20THE%20PAST%2012%20MONTHS%20%28IN%202018%20INFLATION-ADJUSTED%20DOLLARS%29&g=0400000US01,02,04,05,06,08,09,10,12,13,15,16,17,18,19,20,21,22,23,24,25,26,27,28,29,30,31,32,33,34,35,36,37,38,39,40,41,42,44,45,46,47,48,49,50,51,53,54,55,56,72&y=2019&cid=S1901_C01_001E&vintage=2019&layer=VT_2019_040_00_PP_D1))


### Executive Summary

The SAT is a standardized test widely use for college admissions in America. Over the past couple of years, an increasing number of high schools are implementing programs that aims to increase the SAT Participation Rate amongst their students. These programs especially target students whose family circumstances are less fortunate, with the aim of helping these students have a better opportunity of going to college.

At the same time, more colleges are dropping or are considering eliminating SAT scores as part of the college application process. This is because SAT has been viewed by some as not an accurate assessment of a student's ability, and it also serves as an inequitable barrier to entry. For example, a student from a less priviledged background may not have the same access to resources that will help them prepare better for the SAT.

Thus, this project seeks to understand the trends behind SAT Participation Rate and SAT Score. More specifically, does an increase in SAT Participation Rate lead to an increase in SAT Score?

The data does show an overall increase in Participation Rate from 2018 and 2019. Out of 51 states in the merged 
dataset [`sat_scores_2018_and_2019.csv`], 45 states showed either the same or an increase in Participation Rate, whereas 6 states showed a decrease in Participation Rate. This decrease is very minimal though, with the largest decrease being 0.03 (or 3 %)

This distribution of the Participation Rate is multimodal, with clusters observed at the two ends of the spectrum. This is likely due to the fact that some states (~20) are contracted with the College Board to administer the SAT for free. ([source](https://blog.prepscholar.com/which-states-require-the-sat)). 

The data also shows an overall decrease in SAT Score from 2018 to 2019. There is a larger spread of data in 2019 compared to 2018, with a slightly larger standard deviation and a slight decrease in the mean and median.

There is a negative correlation between SAT Participation Rate and SAT Score in both 2018 and 2019

For states that had no change or had an increase in Participation Rate from 2018 to 2019, most of them reported a decrease in SAT Score. 

Out of the 6 states that had a decrease in Participation Rate from 2018 to 2019, 4 states reported an increase in SAT Score.



### Conclusion and Recommendations

Based on the data for 2018 and 2019, it can be concluded that increasing the Participation Rate does not necessarily lead to higher SAT scores. In fact, for most of the states that had a increase in Participation Rate, they also observed a decrease in SAT Score.

The increase in Participation Rate from 2018 to 2019 can be explained by the growing number of states that allow schools to administer the test during the school day, typically free of charge. This increases access for students who historically take the test at lower rates, such as those from low-income families, families with no history of college attendance etc. 

Moreover, as the data confirms, this would also more likely lead to lower SAT scores recorded, especially for states that reported a big increase in SAT Participation Rate. This is because these students will be less likely to score as well as those students who come from affluent backgrounds. Furthermore, students from higher income families, or whose parents are college graduates, are already very likely to take the SAT test. Thus, as a whole, SAT scores will likely to be lower.

Thus, enacting measures that target increasing Participation Rate is a good start to creating more equality and more opportunities for disadvantaged students. However, additional programs and resources that directly help prepare these students for such tests must also be introduced in order to effectively help these students capitalize on these opportunities (Khan Academy's free study plans for example). 

Moreover, in recent years, there is an increasing number of colleges dropping or are considering eliminating SAT Score requirements as part of the application process. To effectively asssss the effectiveness and benefits of eliminating such scoring, a study can be done on the percentage of graduates before and after this change was implemented, as well as the demographic of students that were accepted into the different colleges. If the demographic of students is more varied and the pecentage of graduates increases, this might help push other colleges to drop SAT scoring as part of the application process too.

