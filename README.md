# Fantasy-Cricket
This Project is on a Fantasy Cricket Game. This game can perform the basic operations of a Fantasy Cricket Game. The game follows certain rules to perform, failing which an error message shows up and the user needs to correct that.

Basics of Working of Fantasy Cricket Game:
• User needs to create a fantasy cricket team.
• User can then participate in a contest with this team.
• Each player is assigned with a credit value. There is an upper limit on the total credit points in a team.
• Each player will fall into one of the following categories: batsman, wicket-keeper, bowler, all-rounder.
• During the match, points are assigned to the players based on their performance & category.
• At the end of the match, based on the points, a team with the maximum points that adhere to all the rules will be the winning combination of the best 11 players.

Rules to Create Fantasy Team:
• A team should have 11 players to total
• There should be 1 to 3 all-rounders in the team
• There should be only 1 wicket-keeper in the team
• There should be 3 to 5 batsmen in the team
• There should be 3 to 5 bowlers in the team
• Total credit points of the team should not exceed 1000.

Rules to Calculate Points Scored by each Player:
For Batting
• 1 point for 2 runs scored
• Additional 5 points for a half-century
• Additional 10 points for a century
• 2 points for strike rate (runs/balls faced) of 80-100
• Additional 4 points for strike rate>100
• 1 point for hitting a boundary (four) and 2 points for over boundary (six)

For Bowling
• 10 points for each wicket
• Additional 5 points for three wickets per innings
• Additional 10 points for 5 wickets or more in innings
• 4 points for economy rate (runs given per over) between 3.5 and 4.5
• 7 points for an economy rate between 2 and 3.5
• 10 pointsfor aneconomy rate lessthan2

For Fielding
• 10 points each for catch/stumping/run out.

To run this project, the user needs to first open the "FantasyCricket.py" and run it. Thereafter,  the user can perform his/her desired operations.
