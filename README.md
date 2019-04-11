# Bomberman in process ...

Abstract: Bomberman is one of the most famous video games ever. With more that 70 adaptations, from the first version on MSX, ZX Spectrum and Sharp MZ-700 in 1983 to the last versions available on the PlayStation Network, WiiWare and the Xbox Live Arcade commercialized in 2010. More than 10 millions units have been sold.

The goal of this projet is to create a full implementation of a 3D Bomberman video game.

3D version of Bomberman, functional, and complete with graphics, animations and levels, solo game:

	• The player can acces a main menu allowing him to start a new game, load a save, adjust game settings and exit the game.
	• Different difficulty 
	• To beat the game, the player must win 3 levels. 
	• If the player looses, the game state it clearly and restarting the current level, or issuing a game over. 
	• Sounds! Musics! The main menu and the 3 levels have their own music. Also, every relevant events have trigger a sound, like a bomb exploding, picking up a power up, killing an ennemi, dying, etc.
	• The visual assets in 3D, but the gameplay stay 2D like the original game. For instance, if the player dies, the camera shift its angle and spin around him while the death animation plays, and at the beginning of a level, the camera fly around the level before focusing above the player. A good exemple of a 3D game with a 2D gameplay.
	• Animated 3D models of a bomberman and its ennemies.
	• As stated in the previous section,  main menu allow to customize the game settings. It is possible to customize at least:
		◦ The screen resolution
		◦ Windowed or full screen mode 
		◦ Key bindings
		◦ Music and sounds volumes
	• The game offers a way to save the player’s progression and restore it on demand. 

## Requierements, Install

### MacOsX:
    - brew update && brew install wget sdl2 sdl2_image sdl2_mixer sdl2_ttf

## Single
<img src="https://github.com/vkozhemi/Bomberman/raw/master/img/2.png" width="700">

## Multiplayer
<img src="https://github.com/vkozhemi/Bomberman/raw/master/img/1.png" width="700">

## Game
<img src="https://github.com/vkozhemi/Bomberman/raw/master/img/3.gif">

