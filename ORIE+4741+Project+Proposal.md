

## <p style="text-align: center;"> ORIE 4741 Final Project Proposal </p> 
## <p style="text-align: center;"> Can we predict LOL Game Results?</p>
##### <p style="text-align: right;"> Jiang Zhu, Anqi Ren, Yuhan Li</p> 
##### <p style="text-align: right;"> September 22th, 2017</p>

###### <p style="text-align: center;"> Dataset and Background </p> <br/>
League of Legends is a multiplayer online battle arena video game, which provides hundreds of champions and each with unique ability and battle skills. There are two teams with five members each in one play, and the ultimate goal of the play is to destroy the nexus of the opposing team.<br/>
<br/>
The dataset consists of 51,536 ranked EUW games from the League of Legends along with two json files containing the champion IDs, names, and summoner spell IDs. The game dataset includes various play information. For every play, there are game IDs, game duration (in seconds), season IDs, winner (0=team 1, 1=team 2), first Baron, dragon, tower, blood, inhibitor and Rift Herald (0 = team1, 1 = team2) record, summoner spells taken by each play, the number of tower, inhibitor, Baron, dragon and Rift Herald kills each team has, and the 5 bans of each team shown by champion IDs. <br/>
The dataset is collected from Kaggle. The website is shown below:
https://www.kaggle.com/datasnaek/league-of-legends

###### <p style="text-align: center;">Question </p><br/>
With the information of each game, we are interested in studying whether certain in-game event  would be able to determine the result of a game, as well as understanding and comparing how big the effect is for each in-game event. Specifically, we are proposing the following questions:<br/>
<br/>
How likely will each in-game event (such as first blood / first tower / first Inhibitor / first Baron / first dragon / Baron kills / dragon kills) individually lead to victory? What is the most important factor?<br/>
Whether there is an increased effect on victory by combining these in-game events?<br/>
What is the optimal combination of these in-game events that will lead to victory?<br/>

###### <p style="text-align: center;">Project Value</p><br/>
League of Legends is a very popular video game upon its release in 2009. In 2016, there are over 100 million active players estimated each month. [1] The project would have very broad range of audiences considering the increasing amount of players worldwide. Besides common players, professional teams would also be interested in studying the result of this project to improve their strategies in competitions. <br/>
<br/>
This project would benefit players mainly in terms of developing winning strategy of the game. More specifically, players can use the result to choose in-game events that would most likely lead to victory under different circumstances. The project would also suggest the most important factors in the event which affect victory, so players would tend to pay more attention on those important factors.<br/>

[1] League of Legends. (2017, September 18). Retrieved September 22, 2017, from https://en.wikipedia.org/wiki/League_of_Legends
