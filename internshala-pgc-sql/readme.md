# Analyzing IPL Performance with SQL
## Motive
The primary aim of this project is to demonstrate how data analysis, particularly using SQL, can provide actionable insights into player selection strategies in the IPL auction. This analysis is driven by the idea that teams make multi-million-dollar decisions based on player statistics. Understanding which attributes (e.g., batting average, strike rate, boundary percentage) most affect the auction price can help teams make more informed, data-driven decisions.
____

## Problem Scenarios
### 1.  Batsmen Selection
  The goal is to acquire a mix of aggressive, anchor, and hard-hitting batsmen during the auction, and to build a competitive team for the IPL. This involves:
   - Aggressive Batsmen: These batsmen should have a high strike rate (minimum 500 balls faced), contributing quickly to the team's run rate.
   - Anchor Batsmen: These batsmen should have a good average (and should have played more than two IPL seasons) to bring consistency and stability to the team's innings.
   - Hard-Hitting Batsmen: These players should have a high boundary percentage (number of boundaries divided by total runs scored), having scored the majority of their runs through fours and sixes. They should have also played more than two seasons.

### 2. Bowlers Selection
   In addition to batsmen, selecting the right bowlers is crucial for the team's success. The primary focus should be on two key categories of bowlers: Economical Bowlers and Wicket-Taking Bowlers.
   - Economical Bowlers: These bowlers maintain a low economy rate (runs conceded per over) and are key to controlling the opposition's run rate. The focus is on bowlers who have bowled at least 500 balls with a strong economy.
   - Wicket-Taking Bowlers: These bowlers are crucial for breaking partnerships and taking wickets at critical moments. The goal is to find bowlers with a high strike rate (balls per wicket) who have bowled a minimum of 500 balls.

### 3. All Rounders Selection 
  - All-rounders provide flexibility in both batting and bowling. The objective is to select 2-3 all-rounders who have both a strong batting strike rate and bowling strike rate. They must have faced at least 500 balls and bowled at least 300 balls in the IPL.

___

## Data used
The dataset consists of IPL player performance data from the 1st to the 13th season. 

___

## Tools Used
- **Excel**: Used for initial data exploration and cleaning.
- **SQL**: Utilized for querying and analyzing the IPL dataset to derive insights.
- **PostgreSQL**: Used as the local database to store and process the IPL data efficiently for querying and analysis.
