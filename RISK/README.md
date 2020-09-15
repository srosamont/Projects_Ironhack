
# RISK

Game coded in team with nclee17 during Ironhack Data Analytics Bootcamp


## Game Rules

### Objective:

	- To become the dominant world power.

### Equipments:

	- 3 red dice for the attacker
	- 3 blue dice for the defender
	- 42 territory cards
	- Troops (Number of troops limited only for the game setup but not for the game play) 
Not included in the current version:
	- 42 risk cards with symbols (Infantry, Calvalry, Artillery)
	- 14 mission cards

### Game Setup:

Choose the number of players (2-6), and set up with their names.
The number of troops for each player is determined by the number of players.
If 2 players is selected a 'neutral' player will be added to the board, with troops distributed to defended neutral territories.
Distribute all the territories randomly to the players and place one troop on the territory.
The remaining troops are randomly assigned to the player's terrritories.
Randomise the order of players

### Game Play

This is a turn based game, in each turn the player has 3 phases:

	- Reinforment
	- Attack
	- Manoeuvre
	
#### Phase I: Reinforcement

Players are given extra troops to dispatch onto the owned territories. Therea are 2 ways to obtain troops to reinforce the army:

	- 1 troop for every 3 territories owned.
	- Bonus troops if you own a whole continent, the number depends on which continent is owned.

#### Phase II: Attack

Player can initiate an attack as often as possible. Player announce which territory the troop will be deployed from and attack atttacks which territory, and the number of troops to commit for the attack.

An attack is only possible when the below conditions are met:

	- The atttacking territory is occupied by the player.
	- The two territories are neighbours.
	- The destination territory does not belong to the player.
	- The originated territory must have at least 1 troop stationed behind.

The combat:
Attacker rolls the 3 red dice and the defender rolls the 3 blue dice to decide the fate of their troops committed into the battle.
The player with the higher sum of the dice output added together wins, and the loser will lose a troop.
The combat automatically continues until "last man standing", either attacker successfully conquered the territory and move in with the surviving troops; or defender successfully killed off all the attacking troops and remain stationed with the surviving troops

####Phase III: Manoeuvre

Player can move troops from one (and only one) of territories into one (and only one) of the adjacent territories belonged to the current player. The manoeuvre has to respect the "cannot empty territory rule".

#### End Game

A Player succeeds to conquer 30 territories
