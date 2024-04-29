### NBA Player Usage% and Team Success Data Science Project

#### 1. Project Overview
   - **Objective**: Determine if a ball-dominant playstyle leads to greater team success, measured in SRS (Simple-Rating System) or relative strength of a team.
   - **Hypothesis**:  Teams with a higher usage rate for key players will have a higher positive correlation with their overall team success.
   - **Significance**: NBA teams across over have adapted different playstyles that are dependent on how an offense is coordinated through a primary ball handlers. In the modern age of basketball, there is a nuance of positionless-basketball. In this case, the primary facillator isn't always the point guard. This study investigates how key player impact and their usage rate affect overall team success.

#### 2. Data Collection
   - #### Data on indivudual players were sourced from www.basketball-refrence.com and www.nba.com/stats. Data on team success was sourced from an excel file (attached to repository). The timescale for the data used is based on NBA Regular season stats from 2001-2020 seasons. For each year, the team with the highest relativev strength was selected to represent a baseline for comparison. From here, the 3 players with the Highest MPG and Usage % for each team were selected to represent the team's statistical playstyle. In the case that a player has a higher MPG, but lower Usage Rate in comparison to another player, a judgement was made based off who is more impactful to the team's success.

### Key metrics:

- **PPG (Player points per game)**
- **REB (Player rebounds per game)**
- **AST (Player assists per game)**
- **PPG+AST+REB (Player impact)**
- **USG% (Usage Rate, how often player is in control of the ball)**
- **SRS (Simple-Rating System, relative strength of a team)**
- **Average USG% (takes the average usage amongst the key players of a team)**
- **Average PPG+AST+REB (takes the average PPG+AST+REB amongst the key players of a team)**

For stats such as 'Average PPG+AST+REB' and 'Average USG%', the 3 players selected for each team had their PPG+AST+REB and USG% averaged. These new metrics were used as a baseline for their respective teams when it comes to linear regression later on.

#### 3. Methods and Algorithms
   - **Descriptive Statistics**: Mention any initial statistics or data summaries.
   - **Exploratory Data Analysis (EDA)**: Techniques used to explore the data were visualization, linear regression, and the use of PANDAS.
   - **Regression Analysis**: Regression Anaylsis was performed on 4 different scenarios to investigate the similarities between player statistics and team success stats.

The scenarios are:
   - 'PPG+REB+AST vs USG%'
   - 'AVG USG% vs Team Win/Loss%'
   - 'AVG USG% vs SRS'
   - 'AVG USG% vs AVG of PPG+REB+AST'
     
   - **Model Evaluation**: Only the 'PPG+REB+AST vs USG%' had similarity with an R-score value of 0.68. The rest of the models showed little correlation.

#### 4. Results
   - **Summary of Findings**: The project revealed a strong relationship between a player's usage rate and individual performance stats but showed weak to no correlation with team success indicators like win/loss percentage and SRS.

#### 5. Discussion
   - **Interpretation of Results**: The results suggest that while individual stats may improve with higher usage rates, this doesn't necessarily translate to better team performance or more wins.
   - **Implications**: These findings imply that NBA team strategies should not solely focus on increasing key players' usage rates but also consider other aspects of team play.

#### 6. Limitations and Future Work
   - **Challenges Encountered**: The analysis faced limitations due to the basic nature of the stats used, potentially overlooking deeper insights into player and team performance.
   - **Suggestions for Future Research**: Future research could benefit from incorporating advanced metrics like PER or RPM to unearth the subtle impacts of player usage and identify additional factors that contribute to team success.

#### 7. Conclusion
   - **Final Thoughts**: The study shows that players with the ball a lot has a high impact in terms of PPG+REB+AST, but that doesn't always help the team win games. To really understand why, there needs to be a more indepth anaylsis of advanced statsitics.

#### 8. References
   - **Data Sources**:
      Basketball-Reference.com. (n.d.). Player Index. Retrieved [April 28,2024], from https://www.basketball-reference.com/players/
     National Basketball Association. (n.d.). Advanced Player Stats: 2019-20 Season. Retrieved [April, 28, 2024], from https://www.nba.com/stats/players/advanced?Season=2019-20&TeamID=1610612746&dir=A&sort=MIN

