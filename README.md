# CS-GO-ROUND-WINNER-PREDICTION-USING-MACHINE-LEARNING

This  project aimed at exploring machine learning models' performance on a dataset derived from high-level tournament play in Counter-Strike: Global Offensive (CS:GO) matches. This dataset, originally published by Skybox as part of their CS:GO AI Challenge, contains 700 demos from 2019 and 2020, capturing round snapshots at regular intervals.

#Project Context
CS:GO is a highly tactical first-person shooter game where two teams, Counter-Terrorists (CT) and Terrorists (T), compete in a series of rounds. 
Each match consists of a best-of-30-rounds format, with each round lasting 1 minute and 55 seconds. The first team to win 16 rounds emerges victorious. Teams switch sides after playing 15 rounds, and there are 7 different maps on which matches can take place.

# Objectives
The primary goals of this project are as follows:

- Identify machine learning models that perform optimally on the dataset.
- Determine which features are most indicative of a team winning a round.
- Analyze the correlation between in-game variables (e.g., health, armor, money) and round outcomes.
- Investigate whether certain weapons or equipment are more favorable than others.
- Identify key attributes contributing to a team's success.

# Data Dictionary
The dataset comprises various attributes, each providing insight into the state of a round. Below is a summary of the key variables:

- time_left: Time remaining in the current round.
-ct_score: Current score of the Counter-Terrorist team.
- t_score: Current score of the Terrorist team.
- map: The map being played on (e.g., de_dust2, de_inferno).
- bomb_planted: Boolean indicating whether the bomb has been planted.
- ct_health: Total health of all Counter-Terrorist players.
- t_health: Total health of all Terrorist players.
- ct_armor: Total armor of all Counter-Terrorist players.
- t_armor: Total armor of all Terrorist players.
- ct_money: Total bankroll of all Counter-Terrorist players (in USD).
- t_money: Total bankroll of all Terrorist players (in USD).
- ct_helmets: Number of helmets on the Counter-Terrorist team.
- t_helmets: Number of helmets on the Terrorist team.
- ct_defuse_kits: Number of defuse kits on the Counter-Terrorist team.
- ct_players_alive: Number of alive players on the Counter-Terrorist team.
- t_players_alive: Number of alive players on the Terrorist team.
- ct_weapon_X: Count of Weapon X on the Counter-Terrorist team (e.g., Ak47, Deagle).
- t_weapon_X: Count of Weapon X on the Terrorist team.
- ct_grenade_X: Count of Grenade X on the Counter-Terrorist team (e.g., HeGrenade, Flashbang).
- t_grenade_X: Count of Grenade X on the Terrorist team.
- round_winner: Winner of the round (CT = Counter-Terrorist, T = Terrorist).

# Inspiration
- Which machine learning models demonstrate superior performance on this dataset?
- What features are most predictive of a team winning a round?
- How does the team with the most money fare in terms of round wins?
- Are certain weapons or equipment more advantageous?
- What attributes contribute most to a team's success (e.g., health, armor, money)?
