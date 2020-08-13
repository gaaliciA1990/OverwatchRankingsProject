# Overwatch Competitive Ranking Project

## Objective
This will be an analysis of Overwatch Competitive ranking. An indept anlysis will be conducted into the correlation of having multiple characters as a "main" (most played character(s)) on a player's competitive ranking. The goal is to create a predictive model for competitive ranking based on the last three (3) competitive seasons' data, to determine a player's chance of attaining a higher Skill Rating (SR) based on the number of characters played. A players top characters will be determined using their win/loss/tie statistics for each season. 


## Hypothesis
I believe the more flexible a player is in their competitive match, the higher chance they have of attaining a higher SR. My hypothesis is, a player who "mains" 2-3 characters, as opposed to 1 or more than 3, has a higher flexibility in adapting to a competitive team match, and performing better (higher wins), thus resulting in a higher SR.


## Data Source
Blizzard Overwatch - OmnicMeta (private data set, non disclosure)
* Competitive season 5, 6 and 7.
* player_id (numerical)
* player competitive Skill Rating (SR)
* Player competitive win/loss/draw for each character (26 characters total)

## Results
The final results proved we are unable to predict a players SR based off of the number of characters they played as mains.

While this may appear to be a failure, the results show how well balanced the game design is and points towards a correlation between the total number of games played and a players SR (rank). Blizzards goal with Overwatch is to create a game with characters that are well balanced between each other, menaing no one character can hold all of the power in the game. The data shows that this goal has been accomplished, and the idea that playing more game to improve a players skill is supported with the evidence displayed in this project.
