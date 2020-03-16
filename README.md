# MLB-Baseball-Hall-Of-Fame

check out my post： https://xiangkechen.github.io/2020/03/15/MLB-Baseball-Hall-of-Fame-Prediction/

## Background

This is a 24 hour data challenge. All these are done within 24 hours. So I was unable to improve the model performance as well as the explore more data. 

In this 24 hour data challenge, I completed:

- Basic classification prediction model (codes)
- A presentation slides
- A technical document for data scientist or those who want to replicate my analysis.

-------

The data for this project came from the [Lahman database](http://www.seanlahman.com/baseball-archive/statistics/), a respected record of historical baseball data, which I downloaded.

There are lots of baseball fans around the world. And players who are talented in this area will be honored as **Hall of Fame**. 

This is one of most honorable award in baseball area.

So if we identify which player is more likely to be selected by Hall of Fame, we might have better investment.

- For executives, they can know which players have higher potential
- For advertisement companies, they can know which players might bring higher revenue

## Problem & Task

For this exercise, I am going to analyze Major League Baseball statistics and come up with an implementation of a classifier that indicates if a player is in the baseball Hall of Fame or not, based on the players history performance.

# Data Source

## Environment

* Platform : Google Colaboratory
* Language : Python
* Version: 3.7.4
* Packages :
  * pandas
  * numpy
  * matplotlib
  * Scikit-learn
  * seaborn

* Inital Models : 
  * Decision Tree
  * K Nearest Neighbors
  * Random Forest
  * XGBoost



## Source Table

The data come from Sean Lahman. He summarized the data on his website ([link](http://www.seanlahman.com/)). 

The file contains:

1. **MASTER** - Player names, DOB, and biographical info
2. **Batting** - batting statistics
3. **Pitching** - pitching statistics
4. **Fielding** - fielding statistics  
5. **AllStarFull** - All-Star appearances
6. **Hall of Fame** - Hall of Fame voting data
7. **Managers** - managerial statistics
8. **Teams** - yearly stats and standings 
9. **BattingPost** - post-season batting statistics
10. **PitchingPost** - post-season pitching statistics
11. **TeamFranchises** - franchise information
12. **FieldingOF** - outfield position data  
13. **FieldingPost**- post-season fieldinf data
14. **ManagersHalf** - split season data for managers
15. **TeamsHalf** - split season data for teams
16. **Salaries** - player salary data
17. **SeriesPost** - post-season series information
18. **AwardsManagers** - awards won by managers 
19. **AwardsPlayers** - awards won by players
20. **AwardsShareManagers** - award voting for manager awards
21. **AwardsSharePlayers** - award voting for player awards
22. **Appearances** - details on the positions a player appeared at
23. **Schools** - list of colleges that players attended
24. **CollegePlaying** - list of players and the colleges they attended



For this project, I mainly use `HallofFame`, `Master`, `Batting` table for analysis. 

**More data will come into analysis in the future.**



# Analysis Flow

I followed the below approach to do the analysis. Due to limit time, I was unable to analyze very deep nor could I go through every detail. But the logic is the same as what I showed below.

![](https://hackernoon.com/hn-images/1*oU3LAye3LxFcHg0UePmbSA.png)

Picture Source: [hackernoon](https://hackernoon.com/)



