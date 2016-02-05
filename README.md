# **Clash of Stacks** official rules
**Draft version of 0.1**

Clash of Stacks is a turn based game for two or more players. Each game is a contest between all players. Player with most points wins the game.

### Requirements
Each player needs at least 10 cards in order to play. All players need to have an equal count of cards.

### Set-up
Each player holds their cards and keeps them secret. The player who takes the first turn is decided by randomness (_e.g. highest dice roll or paper-scissors-rock_).
After each turn, the play proceeds  clockwise from the left of the current player.

### Taking turn
When it’s the player’s turn, he must play out a single stack card, action card or pass the turn:
  - **Stack cards** are placed in front of the player and cannot be added to another players stack cards.
  - **Action cards** (_marked with red or blue background_) can be added to any players stack cards.
  - By **passing a turn** to the next player no actions are taken.

### The Web stack
Each players Web stack consists of all stack cards played and all of the action cards added to the players stack.

### Ending the game
The game ends when all players have played out all cards or all players pass in a single round.

### Additional rules
  - For a valid Web stack __Front-end__ and __Back-end__ need to be unlocked. If in the end of the game these are not unlocked or lost with an action card, the Web stack is not valid, therefore the player cannot win.

### Counting the score
Each player counts his personal score. Each attribute (_e.g. Stack, Scale or Deploy_) is summed individually between all the player’s Web stack cards considering Superpower effects and their relationships between other cards.

Each attribute sum is then multiplied by these given indexes:
> Attribute types and indexes are not finalised; Work in progress

__The final score is the sum of all attribute values.__


### Determining the winner
The player with the largest Web stack score wins. In case of even scores, all players with the even score are declared as winners.
