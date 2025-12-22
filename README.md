⚽ Player Stats Dashboard — Sports Performance Analytics
📌 Overview

The Player Stats Dashboard is the first page of the Sports Performance Analytics project built using Power BI.
This page focuses on individual player performance analysis, allowing users to explore scoring efficiency, match participation, and top scorers across FIFA World Cup seasons.

The dashboard is fully interactive, filter-driven, and designed for football analytics use cases.

<img width="1276" height="730" alt="Screenshot 2025-12-22 115608" src="https://github.com/user-attachments/assets/7039724c-3731-4f83-be77-70c3778187cb" />

🎯 Objectives

Analyze player-level performance metrics

Identify top goal scorers

Measure scoring efficiency and strike rate

Enable dynamic filtering by team, season, position, venue, and match result

📊 Key KPIs (Top Cards)
KPI	Description
Total Matches	Total number of matches played based on filters
Average Score	Average goals scored per match
Strike Rate	Goals scored per 90 minutes played
📈 Visual Components
🔹 1. Player Performance Table

Columns:

Player Name

Total Goals

Total Assists

Total Minutes Played

Purpose:

Compare individual player contributions

Sort players by goals or minutes played

Analyze attacking involvement

🔹 2. Top 10 Goal Scorers (Bar Chart)

Displays Top 10 players by total goals

Dynamically updates with slicers

Helps quickly identify top scorers

🎛 Interactive Filters (Slicers)

The following slicers are available at the top of the dashboard:

Team

World Cup Year (Range)

Match Result

Position

Venue

These slicers allow users to:

Drill down into specific seasons or teams

Compare player performance across different conditions

Perform focused analysis with real-time updates

🧮 Key Metrics Logic (DAX-Based)

Total Matches → Distinct count of Match IDs

Average Score → Total Goals ÷ Total Matches

Strike Rate → (Goals × 90) ÷ Minutes Played

Top Scorers → Ranked dynamically using RANKX

All calculations are handled through optimized DAX measures.

🏆 Team Performance Dashboard — Sports Performance Analytics
📌 Overview

The Team Performance Dashboard is the second page of the Sports Performance Analytics project built using Power BI.
This page focuses on team-level performance evaluation, enabling comparison of wins, goal contributions, and scoring efficiency across FIFA World Cup teams.

It provides a clear, KPI-driven view of how teams perform under different conditions such as venue, season, and match outcomes.


<img width="1276" height="727" alt="Screenshot 2025-12-22 115627" src="https://github.com/user-attachments/assets/c09e4d24-6d3b-4d85-aae9-d92a098ddae4" />

🎯 Objectives

Compare team performance using win percentage

Analyze goal contribution distribution across teams

Measure scoring efficiency using shot conversion rate

Identify top-performing teams by wins

📊 Key KPIs (Top Cards)
KPI	Description
Win %	Percentage of matches won by selected teams
Player Contribution %	Percentage of team goals contributed by players
Shot Conversion %	Goals scored per shot attempted
📈 Visual Components
🔹 1. Team Performance Matrix

Columns:

Team

Win %

Total Goals

Total Goals Conceded

Purpose:

Side-by-side team comparison

Conditional formatting highlights performance strength

Quickly identify strong and weak teams

🔹 2. Wins by Team (Bar Chart)

Displays total wins per team

Sorted in descending order

Highlights top-performing teams in tournaments

🔹 3. Goal Contribution Share (Pie Chart)

Shows proportion of goals contributed by each team

Useful for understanding offensive dominance

Automatically updates based on filters

🎛 Interactive Filters (Slicers)

The dashboard includes the following slicers:

Team

World Cup Year (Range)

Match Result

Position

Venue

These slicers allow users to:

Drill into specific teams or seasons

Compare team performance across venues

Analyze results by match outcomes

🧮 Key Metrics Logic (DAX-Based)

Win % → Total Wins ÷ Total Matches

Player Contribution % → Player Goal Contribution ÷ Team Goals

Shot Conversion % → Goals ÷ Shots

Wins by Team → Sum of Win Flag grouped by Team

All KPIs are dynamically recalculated based on slicer selections.


📈 Season Analytics & Predictive Insights — Sports Performance Dashboard
📌 Overview

The Season Analytics & Predictive Insights page is the third and most analytical section of the Sports Performance Dashboard built using Power BI.
This page focuses on multi-season performance trends, team consistency, and basic predictive indicators to evaluate success patterns across FIFA World Cup tournaments.

It helps users understand how teams and players evolve over time and identify performance stability and efficiency.


<img width="1277" height="730" alt="Screenshot 2025-12-22 115648" src="https://github.com/user-attachments/assets/45629818-44ff-49f2-bc0a-0d0af1b7bc6b" />

🎯 Objectives

Analyze goal trends across World Cup seasons

Measure team consistency and stability

Evaluate win probability using historical data

Identify relationships between shots and goals

Compare team performance across multiple seasons

📊 Key KPIs (Top Cards)
KPI	Description
Win Probability	Likelihood of winning based on historical results
Consistency Index	Measures stability of team performance across matches
📈 Visual Components
🔹 1. Goals Trend by World Cup Year (Line Chart)

Displays total goals scored across seasons

Highlights peaks and dips in tournament scoring trends

Useful for understanding era-wise performance changes

🔹 2. Team vs Season Performance (Heatmap Matrix)

Rows: Team
Columns: World Cup Year
Values: Total Goals

Purpose:

Quickly identify strong and weak seasons for each team

Color-coded performance intensity

Enables fast season-to-season comparison

🔹 3. Shots vs Goals Relationship (Scatter Chart)

X-Axis: Total Shots

Y-Axis: Total Goals

Data Points: Players

Purpose:

Analyze scoring efficiency

Identify high-conversion players

Detect outliers (many shots, few goals)

🎛 Interactive Filters (Slicers)

Available slicers:

Team

World Cup Year (Range)

Match Result

Position

Venue

These filters allow:

Season-specific analysis

Venue-based performance evaluation

Player and team segmentation

🧮 Predictive & Analytical Logic (DAX-Based)

Win Probability → Wins ÷ (Wins + Losses)

Consistency Index → Average Goals ÷ Standard Deviation of Goals

Performance Trends → Aggregated season-wise goal metrics

These measures provide directional predictive insights, not machine-learning predictions.


🏗 Data Model

Fact Table: Fact_Sports

Dimensions: Team, Player, Season, Match Result

Schema: Star Schema

This design ensures:

Accurate seasonal aggregation

High performance with slicers

Scalable analytics framework

<img width="694" height="622" alt="Screenshot 2025-12-22 123702" src="https://github.com/user-attachments/assets/58efa6c7-688f-4a28-bdc7-7e7ca3eee499" />










