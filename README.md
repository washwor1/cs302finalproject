# cs 302 final project - Unreal Engine 5 First Person Shooter

This is our (Jay Ashworth and Andy Zeng) final project for cs302. The game is built on the brand new Unreal Engine 5, and features a versus multiplayer mode where you can go head to head with a friend over lan and a singleplayer "zombie-esque" mode where you can battle with a NPC AI that will keep respawning and attacking you until you die or get bored - whichever comes first.

# How to play it/requirements

Unfortunately, the game engine being in beta, we have a couple bugs that have come up that won't allow us to get past the "cooking" stage of package development despite each of our individual packages compiling. The game is technically compiled/built, it is just not in an executable format. Therefore, if you want to play the game you have to do so in the game editor. 

If prompted, we can provide another demo of our game in youtube format if you don't want to go through the trouble of installing Unreal Engine.

-To Get it Running-
1. Install the Epic Games launcher here https://www.epicgames.com/store/en-US/download
2. Create an account and download Unreal Engine 5 from the store (It is pretty large 50+GB so keep that in mind)
3. Open the project executable and select Unreal version 5.0.
4. It should by default open you to the main menu level and you just hit "play" at the top to start and instance of the game.
-If it does not open up the "blank level" map, you can navigate to it by going to Content/Level/blank level-

-It is also worth noting that my AI may not work properly with the downloaded version because unreal almost always resets 2-3 of my blackboard variables to their default value when I restart the editor regardless of whether I save it and compile or not-

# User Manual
Playing is pretty self explanatory if you've ever played a first person shooter, but I will give a brief explanation.

Controls:
WASD: Movement
LMB: Shoot
RMB: Aim
Space: Jump
Shift: Sprint
C: Crouch
P/ESC: Pause
G: Grenade

Singleplayer:
This is basically an arcade style mode where you keep killing the zombie or bot until you get killed or get bored. The only objective of this mode is to have fun.

Multiplayer: 
In this mode, the objective is to attack the other player until one of you gets killed. There is a time limit of 10 minutes.

# Known Bugs/Flaws
-The project will not cook due to an engine bug so we cannot package it properly.

-There is an issue where closing and reopening the project will reset some variable configuration of the AI back to their default value, causing its patrol funcitonality to not work at all unless it is reconfigured manually.

-The character stutters a lot in the editor especially when there is a lot of lag. 

-The AI only spawns on one side of the singleplayer map.

-The AI will always run back to where it was killed upon being respawned, so it can lead to some wonky behavior if you leave that area.

-There is another bug involving the game engine where, upon joining a multiplayer world, a configured landscape will cause the game to crash due to a heightmap error. Because of this, the ground texture for multiplayer is blank and looks bad. (better than it crashing i suppose).

-Your health can display a negative value upon death, although this is only a visual defect and doesn't affect gameplay.

-The death menu is not centered right on some displays

-Forgot to remove herobrine
