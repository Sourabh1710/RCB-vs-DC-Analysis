## IPL 2024 RCB vs DC Match Analysis
## Project Overview
This project analyzes the IPL 2024 match between Royal Challengers Bangalore (RCB) and Delhi Capitals (DC) using Python. By examining ball-by-ball data, I explore scoring patterns, individual performances, bowling impacts, partnerships, and key turning points to understand what drove RCB’s victory. This project is a key part of my data science portfolio, showcasing my skills in data analysis and visualization.

## Dataset
The dataset includes ball-by-ball details with the following columns:

team: Batting team (RCB or DC)
over: Over number
batter: Batsman facing the delivery
bowler: Bowler delivering the ball
non_striker: Non-striker batsman
runs_batter: Runs scored by the batter
runs_extras: Extra runs (e.g., wides, no-balls)
runs_total: Total runs per delivery
player_out: Player dismissed (if any)
wicket_kind: Type of dismissal
fielders: Fielders involved in dismissal
## Objective
The primary objectives are:

To analyze run distribution and scoring trends.
To identify top performers (batters and bowlers).
To evaluate partnerships and phase-wise performance.
To determine turning points that shaped the match outcome.
## Libraries Used
pandas <br>
numpy <br>
matplotlib <br>
seaborn <br>
## Data Cleaning and Preprocessing
The dataset contains null values, but I retained them to preserve data integrity, as dropping or filling could distort the analysis.

## Run Distribution Per Over
RCB showed aggressive scoring with notable spikes, while DC had a steadier but less steep run rate.


![Run Distribution Per Over](https://github.com/Sourabh1710/RCB-vs-DC-Analysis/blob/main/images/Run%20Distribution%20Per%20Over.png)

## Top Scorers
AR Patel (DC) led with over 50 runs, followed closely by RM Patidar (RCB) nearing 50.


![Top Scorers Bar Chart](https://github.com/Sourabh1710/RCB-vs-DC-Analysis/blob/main/images/Top%20Scorer%20From%20Each%20Team.png)

## Bowling Performance
Bowlers from both teams took wickets, with economy rates varying; RCB’s bowlers were particularly effective in key overs.


![Bowling Performance Plot](https://github.com/Sourabh1710/RCB-vs-DC-Analysis/blob/main/images/Bowling%20Analysis-%20Wickets%20and%20Economy%20Rates.png)

## Dismissal Types
A pie chart reveals how wickets fell, shedding light on pitch and fielding dynamics.


![Dismissal Types Pie Chart](https://github.com/Sourabh1710/RCB-vs-DC-Analysis/blob/main/images/Types%20of%20Dismissals.png)

## Partnerships Analysis
Key partnerships exceeding 20 runs significantly influenced the match.


![Partnerships Bar Chart](https://github.com/Sourabh1710/RCB-vs-DC-Analysis/blob/main/images/Significant%20Batting%20Partnerships.png)

## Phase Analysis
Powerplay: RCB lost more wickets than DC.
Middle: Both peaked, with DC slightly ahead.
Death: RCB’s run rate dropped with wicket losses, while DC held steady.

![Phase Analysis Plot](https://github.com/Sourabh1710/RCB-vs-DC-Analysis/blob/main/images/Phase%20Analysis-%20Runs%20and%20Wickets.png)

## Strike Rate Analysis
Top performers:

J Fraser-McGurk (DC): 262.50
Virat Kohli (RCB): 192.86
RM Patidar (RCB): 152.94
Strike rates peaked in the Middle (Fraser-McGurk) and Death (Kohli, Patidar) phases.


![Strike Rate by Phase Bar Chart](https://github.com/Sourabh1710/RCB-vs-DC-Analysis/blob/main/images/Strike%20Rate%20Across%20Different%20Phases%20for%20Top%20Performers.png)

## Turning Points
RCB’s steeper cumulative run rate and timely wickets disrupted DC’s momentum, especially post-Middle overs.


![Cumulative Run Rate Plot](https://github.com/Sourabh1710/RCB-vs-DC-Analysis/blob/main/images/Cumulative%20Runs%20with%20Wickets%20for%20RCB%20and%20DC.png)

![Run Rate Per Over Plot](https://github.com/Sourabh1710/RCB-vs-DC-Analysis/blob/main/images/Run%20Rate%20Per%20Over%20Both%20Teams.png)

## Conclusion
RCB’s victory stemmed from consistent scoring, strategic bowling, and resilience despite wickets. Standout performances from Patidar, Kohli, and effective partnerships underscored their edge. This analysis demonstrates my ability to derive actionable insights from sports data.

## Author
Sourabh Sonker <br>
Data Scientist
