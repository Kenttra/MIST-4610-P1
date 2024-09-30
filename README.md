# MIST-4610-P1
### Group 2:
Kent Tran - 811696100 - https://github.com/Kenttra/MIST-4610-P1

Shaan Bhagat - 811542876 - https://github.com/Shaan-Bhagat/MIST-4610-Project-1
#### Project Description
Our team decided to model a database that supports fantasy football analysis, focusing on player statistics, game outcomes, and team performance across multiple leagues. In our project's database design, we created 12 entities to encapsulate all relevant information, establishing relationships between these entities to form a comprehensive data model.From the perspective of a fantasy football league, we modeled teams, players, and games to represent the core components of player statistics and team performance. From there, we introduced entities that manage player scoring data, game results, and player rankings to facilitate performance tracking and comparison across teams.On the analysis side of the model, we created entities to evaluate player performance, such as weekly projections and player health status, helping to predict future outcomes and identify potential draft picks or trades. Additionally, we integrated a system to track league standings, manage team rosters, and evaluate player performance metrics, enabling more informed decisions for team management and roster adjustments.This scenario illustrates how our solution provides a comprehensive framework for managing fantasy football data, tracking player statistics, league performance, and optimizing team decisions. It helps identify trends in player performance, set up teams, and even predict future outcomes based on historical data.
### Data Model 
![Data_Model](https://github.com/Kenttra/MIST-4610-P1/blob/main/mist4610-p1%20data%20model.png)
### Data Dictionary
![Dic 1](https://github.com/Shaan-Bhagat/MIST-4610-Project-1/blob/main/Screenshot%202024-09-30%20at%201.02.33%20AM.png)
![Dic 2](https://github.com/Shaan-Bhagat/MIST-4610-Project-1/blob/main/Screenshot%202024-09-30%20at%201.02.39%20AM.png)
![Dic 3](https://github.com/Shaan-Bhagat/MIST-4610-Project-1/blob/main/Screenshot%202024-09-30%20at%201.02.43%20AM.png)
![Dic 4](https://github.com/Shaan-Bhagat/MIST-4610-Project-1/blob/main/Screenshot%202024-09-30%20at%201.02.48%20AM.png)
![Dic 5](https://github.com/Shaan-Bhagat/MIST-4610-Project-1/blob/main/Screenshot%202024-09-30%20at%201.02.58%20AM.png)
![Dic 6](https://github.com/Shaan-Bhagat/MIST-4610-Project-1/blob/main/Screenshot%202024-09-30%20at%201.03.04%20AM.png)
![Dic 7](https://github.com/Shaan-Bhagat/MIST-4610-Project-1/blob/main/Screenshot%202024-09-30%20at%201.03.10%20AM.png)
![Dic 8](https://github.com/Shaan-Bhagat/MIST-4610-Project-1/blob/main/Screenshot%202024-09-30%20at%201.03.14%20AM.png)
### Queries
#1. This query joins Player and PlayerStatistics tables based on the PlayerID and retrieves player information, such as name, position and team and also retrieves their game statistics, such as yards and touchdowns. This is useful to compare each players statistics.
![Q1](https://github.com/Kenttra/MIST-4610-P1/blob/main/Q1)

#2. This query selects all columns from the Player table where the players position matches “QB” using REGEXP. This is useful to sort out each position in the data, taking a look at all players both available and on rosters.
![Q2](https://github.com/Kenttra/MIST-4610-P1/blob/main/Q2)

#3.Selects all teams and finds their total number of wins. This is useful to see which teams are performing the best and worst at any given time. And the managers can decide whether or not they should trade.
![Q3](https://github.com/lwh12347/Mist-4610/blob/main/Q3.png)

#4.Selects only teams who score an average greater than 80 points. This query is useful for displaying scoring numbers across the league. This type of query is important for determining which teams perform at a certain level to show the general performance of the league while excluding outliers.
![Q4](https://github.com/lwh12347/Mist-4610/blob/main/Q4.png)

#9.Select teams whose average points scored are higher than league-wide average points scored by all teams.

![Q9](https://github.com/SahilPnc/MIST-4610-Project-1-/blob/main/Q9.png)

#10.Retrieve the list of free agent players from the Player table and sort them by their position.

![Q10](https://github.com/SahilPnc/MIST-4610-Project-1-/blob/main/Q10.png)

### Matrix

