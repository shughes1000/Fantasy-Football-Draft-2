# Proposal

### Problem Statement
**Statement**:
What is the value of each position at a given draft pick in a fantasy football draft?

**Background**:
In fantasy football, fantasy owners start the year by drafting their fantasy football team. 
This is the most important day in the fantasy season because it determines who many of your key players are. 

**Why is it interesting?**
The fantasy football community has long debated which positions are most valuable (more on this later). 
My project could provide further and more advanced insight to help quantify the values of each position at a given draft pick in a fantasy football draft. 

**Who is interested?**
According to ESPN, 40 million people play fantasy football in the United States. 
Anyone who plays fantasy football and wants to win should be interested in optimizing their drafting strategy. 

**What is known?**
Originally, many thought that quarterbacks are the most valuable position because they score the most fantasy points and they are the most valuable in real football. 
However, it is now widely accepted that running backs are the most valuable position in fantasy football because a top running back scores significantly more fantasy points than an average running back. 
For example, the number 1 ranked running back, Jonathan Taylor, scored 22.8 fantasy points per week, whereas the number ten ranked running back Antonio Gibson, scored 13.8 fantasy points per week. 
Likewise, the number 1 ranked quarterback, Josh Allen, scored 24.7 fantasy points per week, whereas the number ten ranked quarterback Dak Prescott, scored 19.7 fantasy points per week. 
While Josh Allen may have averaged more fantasy points than Jonathan Taylor, his value is still lower because of his point total relative to the others at his position. 

**References**
- [ESPN Fantasy Football](https://www.espn.com/fantasy/football/)
- [FantasyPros Fantasy Football](https://www.fantasypros.com/nfl/)

### Data
All of the data I need can be found on FantasyPro's website. For example, https://www.fantasypros.com/nfl/reports/leaders/ppr.php?year=2019&start=1&end=16 has information on every single fantasy football player who scored in 2019. 
Also, https://www.fantasypros.com/nfl/adp/ppr-overall.php?year=2019 contains information on the player's draft rankings and average draft position by fantasy owners (ADP) in 2019. 
To get the information from different years, I can simply adjust the year in the URL. 

### Analytic Tasks
This is a project that I originally completed my senior year of high school, and I try to update it as I learn more about statistics and machine learning. 
My most recent version of the project can be found [here](https://github.com/shughes1000/Fantasy-Football-Draft). 
I think I can improve on this project by using the rankings that were given from different fantasy football websites as predictors, as well as my newfounded knowledge that I have acquired in this class. 
I will use splines to determine the expected number of fantasy points for a given player based on the information a fantasy owner would have on draft day. 
From here, we can take the derivative of this to determine the expected value of the fantasy position at a given point in the draft. 
After we do this, we can graph our results to visualize our findings in a way that fantasy owners would be able to understand. 