# CS 4550 Project Description
Group: 8
Members: James Tracy

### Overview
This project is a spectator and player portal for the online game [League of Legends](https://na.leagueoflegends.com/en/). It allows users to spectate games, easily see which pro-players are online and in-game, view esports data, as well as track their own in-game statistics and progress.
### Types of users
1. Spectator - this user may or not play the game, but is interested in watching matches/follows e-sports.
**Goals:**
	- To view which pro/high-level matches are in-progress.
	- To be able to spectate these matches.
	- To view e-sports statistics.
2. Player - this user plays the game, and will have their own login on the service. They may be interested in spectating/e-sports, but may also be interested in their own performance and progress.
**Goals**
	- To view their own performance statistics.
	- To track their own progress and view match history.

### Strategy
This service will keep track of pro-player / high-elo accounts in order to feed spectator information. It will allow spectators to quickly see which matches are in-progress and ready to be spectated. There will also be an e-sports page for e-sports fans.

There will be a login for players who wish to keep track of their own statistics. Players will have a profile which gets updated as they play more games. The profile will have multiple tabs to display different game-statistics. Players will only be able to see in-depth stats for their own profile, but will be able to look at profile summaries for other players.

###API
This service will primarily interact with the [riot API](https://developer.riotgames.com/apis).

