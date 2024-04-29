### NBA Player Usage% and Team Success Data Science Project

#### 1. Project Overview
   - **Objective**: Determine if a ball-dominant playstyle leads to greater team success, measured in SRS (Simple-Rating System) or relative strength of a team.
   - **Hypothesis**:  Teams with a higher usage rate for key players will have a higher positive correlation with their overall team success.
   - **Significance**: NBA teams across over have adapted different playstyles that are dependent on how an offense is coordinated through a primary ball handlers. In the modern age of basketball, there is a nuance of positionless-basketball. In this case, the primary facillator isn't always the point guard. This study investigates how key player impact and their usage rate affect overall team success.

#### 2. Data Collection
   - #### Data on indivudual players were sourced from www.basketball-refrence.com and www.nba.com/stats. Data on team success was sourced from an excel file (attached to repository).

### Key metrics:

- **PPG (Player points per game)**
- **REB (Player rebounds per game)**
- **AST (Player assists per game)**
- **PPG+AST+REB (Player impact)**
- **USG% (Usage Rate, how often player is in control of the ball)**
- **SRS (Simple-Rating System, relative strength of a team)**
- **Average USG% (takes the average usage amongst the key players of a team)**
- **Average PPG+AST+REB (takes the average PPG+AST+REB amongst the key players of a team)**


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
   - **Summary of Findings**: Provide a brief overview of key findings without going into too much detail.

#### 5. Discussion
   - **Interpretation of Results**: Discuss what the findings mean in the context of your hypothesis.
   - **Implications**: Suggest what these results might imply for team management or strategy.

#### 6. Limitations and Future Work
   - **Challenges Encountered**: Discuss any limitations or challenges faced during the project.
   - **Suggestions for Future Research**: Propose areas for further investigation or other related hypotheses to test.

#### 7. Conclusion
   - **Final Thoughts**: Summarize the project's outcomes and any concluding thoughts.

#### 8. References
   - **Data Sources**: List all data sources used in your project.
   - **Citations**: Include citations for any tools, libraries, or external resources that assisted in the project.

#### 9. Appendices
   - **Code**: Provide links to any repositories or supplementary materials that support your project.


