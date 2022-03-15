# robot-gladiators
Wrap the game logic in a startGame() function
When the player is defeated or there are no more enemies, call an endGame() function that:
Alerts the player's total stats
Asks the player if they want to play again
If yes, call startGame() to restart the game
After the player skips or defeats an enemy (and there are still more robots to fight):
Ask the player if they want to "shop"
If no, continue as normal
If yes, call the shop() function
In the shop() function, ask player if they want to "refill" health, "upgrade" attack, or "leave" the shop
If refill, subtract money points from player and increase health
If upgrade, subtract money points from player and increase attack power
If leave, alert goodbye and exit the function
If any other invalid option, call shop() again
