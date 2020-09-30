# sus.
## by intElligence

**SETTING:** 

    Game is based off a distant year where a deadly zombie apocalypse has taken over the world. Humankind's last known survivors have been working towards the repair of a bunker to process a possible antidote to the infection. However, the INFECTED find ways to get into bunkers and stay alive by infecting others.

**OUTLINE:**
    PLAYERS:
	    - 5-10 players
	    - 1 player INFECTED (ZOMB_MAIN)

    OBJECTIVE:
	- NON INFECTED players have the objective of completing tasks that correspond to repair of the bunker for survival.
	- Logic: Completion of all tasks by all NON INFECTED players awards them with the antidote and hence they cannot be INFECTED and the game ends.
	
	- ZOMB_MAIN has the objective to infect all other players. All players INFECTED by ZOMB_MAIN (ZOMB_SUBS), are not allowed to reveal that they have been INFECTED. Any non infected player passing close by ZOMB_SUBS, gets INFECTED too. All ZOMB_SUBS will survive only till the next "Emergency Call" made by anyone. On the event of an "Emergency Call", all ZOMB_SUBS will succumb to the infection and die.
	- Logic: ZOMB_MAIN needs to click a button when near a player to infect him and this action triggers the color of the newly INFECTED player to flash RED for a second. Hence, ZOMB_MAIN needs to ensure that no one is nearby to spot the RED flash and subsequently vote to kick him. However, ZOMB_SUBS do not need to press any button and anyone crossing nearby, will get INFECTED and become a new ZOMB_SUB. 
	
	EMERGENCY CALL: 
        *Players who are dead CANNOT talk or voice opinions during the call*
	    Only currently NON INFECTED players will have an option to make an "EMERGENCY CALL", which pauses the gameplay and allows all alive players to vote for a player to be "kicked out for suspected infection". On initiating the "Emergency Call", all ZOMB_SUBS will be announced dead. All players ALIVE can voice their opinions through the in-game text chat and take a decision on whom to vote out based on the discussions. They can also opt to skip voting. Player to be kicked out will be determined based on majority vote. If majority vote for one player to be kicked, he will be kicked. 
	    Possible game paths:
			§ Player does not get kicked out (no majority vote): Game continues and voters are notified that no one was kicked.
			§ Player kicked out was ZOMB_MAIN: Game ends and all initially NON INFECTED players win.
			§ Player kicked out was not INFECTED: Game continues and all voters will be informed that player was kicked out and "was not INFECTED".

	- Game end: 
		○ Game ends if:
			§ All tasks are completed (all initially NON INFECTED players win)
			§ ZOMB_MAIN is kicked(all initially NON INFECTED players win)
			§ One NON INFECTED player remains (ZOMB_MAIN wins)


