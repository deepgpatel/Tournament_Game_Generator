# Tournament Scheduler

This program allows you to schedule games for an end-of-year tournament. It will determine the games played in the first round of the tournament based on the number of teams, the names of the teams, the number of games played by each team, and the number of wins each team had during the regular season.

## Getting Started

To run this program, simply execute the `Tournament_Game_Generator.py` file in your Python environment. You will be prompted to enter the number of teams, the names of each team, the number of games played by each team, and the number of wins each team had during the regular season.

## Input Constraints

There are always at least 2 teams in the tournament.
Each team plays every other team at least once in the regular season.
All team names contain at most 2 words and at least 2 characters.
Each team has at minimum 0 wins and no more wins than the number of games they played.


## Output

The program will output the games that should be played in the first round of the tournament. The first game outputted should contain the team with the most regular season wins, the second game should contain the team with the second most regular season wins, etc. The home team of each game should be the team with the least wins of the two, if there is a tie in wins your program can choose any appropriate team.