# Project1-Group3: Less moneyball? The influence of the Competitive Balance Tax on Major League   Baseball from 1985 to 2015

UofM Bootcamp Project 1 by Group 3 (baseball data)

## Contributors
Clayton Knight,
Molly Ingram,
Wanderson Oliveria


## Project Overview

In 1997, Major League Baseball (MLB) introduced the Competitive Balance Tax (CBT) as a measure to deter teams from exploiting a spending advantage without consequences. The goal was to level the playing field and prevent teams from gaining an unfair advantage in acquiring higher-quality players by overspending. This project assess how the CBT may have impacted team behavior and performance.  

We use a baseball dataset compiled by Sean Lahman and shared via kaggle (see link in Credits). We limit our sample to the MLB seasons corresponding to calender years 1985 to 2015. During that time period, new teams (franchises) joined the league so we restrict our sample to the 26 teams present in all years of the study period. The resulting dataset contains 806 observations uniquely identified by year-team pair.  We supplement this data with information on the tax thresholds set by the MLB association.

The MLB implemented the competitive balance tax in 1997 to reduce anti-competitive behavior in the league.The first agreement stated that the top five salary teams in each year would pay a 34% fine on each dollar a team spent beyond halfway between the salaries of the fifth and sixth teams.
For example, if the fifth-highest salary team had a payroll of $100 million and the sixth-highest salary team had a payroll of $98 million, the top five teams would pay 34% on each dollar they spent over $99 million.
The MLB luxury tax was eliminated from 2000 to 2002, and MLB brought it back with a new change to the system.

The system today is based on the 2002 collective bargaining agreement. Instead of putting a level between the 5th and 6th teams, they decided to set a threshold that a team could not pass without a fee. Taxes are factored on each dollar going over the threshold.
2003 - 2011, first-time offenders would pay a fee of 17.5% of excess payrolls (later increased to 22.5%), second-time offenders would pay 30%, and third-time offenders would pay 40%.
2012 - 2015, after seeing teams go over more than three times, the agreement added a 50% taxation level when teams went over the limit four or more times. (These offenses must be in consecutive years for these percentages. If a team falls below the threshold one year the penalty resets the next year to the "first offense")  

### Repository Organization


## Project Analysis
To better understand how the CBT impacted MLB teams, we break the topic into three questions: 1) Did the teams' spending on player salaries change, 2) Did more spent on players salaries led to more wins, and 3) Did was player talent better distributed.  An analysis of each question follows.


### Question 1: Did implementation of penalty system eventually discipline the teams? (Led by Clayton)

Despite occasional fluctuations in the gap between teams with the highest and lowest salaries following the implementation of the CBT, the sustained increase in average salaries suggests that teams have not collectively exhibited greater fiscal discipline to circumvent CBT payments.  
<img src="Output\Disparity Fig.png"
 alt="Disparity"
style="display: inline-block; margin: 0 auto; max-width: 300px">

<img src="Output\Avg Regression Fig.png"
 alt="Avg Regression"
style="display: inline-block; margin: 0 auto; max-width: 300px">

### Question 2: What was the most dominant team during the 30-year period and its correlation to salary? (Led by Wanderson)
After analyzing the data, was showed that the New York Yankees (NYY) won most games during 30 years, hence being the most dominant team for a 30 years period. Potentially due to ownership and good management, by spending money on the team in order to win games.Overall, from 1985 to 2015 Teams have showed an exponential growth in salary, meaning teams are investing more in their players, however, after analyzing the data, concluded that there is no correlation between wins and salary spent per each team. One Example is (ANA), which won the most games in 2014 and had a total team salary spent of approx. $121M, that same year, (SFG) won 88 games and total spent of approx.163M.
(NYY), the most dominant team, had spent the most and won the most games in 2009, however, the following year, 2010, it didn’t win the most games and still was the team that spent the most, approx. $206M. Hence, there is no correlation between wins and salary pear year for the most dominant team.

<img src="Graphic 1.png"
 alt="Correlations"
 title="Optional title"
style="display: inline-block; margin: 0 auto; max-width: 300px">

<img src="Graphic 2.png"
 alt="Correlations"
 title="Optional title"
style="display: inline-block; margin: 0 auto; max-width: 300px">



### Question 3: Did the CBT generate a more equitable distribution of talent? (Led by Molly)


<img src="Output\performance correlations.png"
 alt="Correlations"
style="display: inline-block; margin: 0 auto; max-width: 300px">



### Conclusion


## Thanks/Credits
Thanks for Vishal Bhatnagar, our original fourth group member. Thanks to Sam Espe, Hunter Hollis, and Randy Sendek for their troubleshooting support.  All errors are our own.

Data was retrieved from <https://www.kaggle.com/datasets/open-source-sports/baseball-databank>

Random Forest code was adapted from <https://towardsdatascience.com/random-forest-in-python-24d0893d51c0>