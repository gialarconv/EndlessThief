# EndlessThief
Endless Thief is a Endless Runner Game, created with the purpose of complying with the requirements given by Gamaga.
Using URP
Unity Version: 2019.4.21f

Assets Ussing in Game.

Polygon City from Synty Studio: https://assetstore.unity.com/packages/3d/environments/urban/polygon-city-pack-95214
ToonListShader from Colin Leung: https://github.com/ColinLeung-NiloCat/UnityURPToonLitShaderExample
Mini first person controller: https://assetstore.unity.com/packages/tools/input-management/mini-first-person-controller-174710
Using Mixamo Animations.
https://www.mixamo.com/

HOW to play. 
In PC use A or Left Arrow to move to Left - use D or Right Arror to move to Right - Use Space To jump (It's not necessary to use).
In android use lower corners to move.

About Logic

GameManager is the Singleton class connected with Scriptable Object call Player Settings.

Player Settings contain the game logic, like time, speed enemy and player, health and score.

Player use 4 script to the correct function:
Player Movement to calculate the movemente and translation. 
Jump: To jump, it's really not necesarry, but for future can be usable.
Player Manager: Contain Game Manager parameters and Trigger actions.
Ground Check: To check if player is on ground or not.


Are two different enemies, static and moving.

Static are shooting when the raycasthit check if the hit object is the player
The moving enemies go in they go in the opposite direction of the player and respawn in the SpawnRunEnemy points.

The project have the all necessary script to scalable, Spawners, Enemies Stats, Player Stats, Game Timer, Sound FX Controller, Scene Controller.
