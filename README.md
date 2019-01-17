# Graveyard-Archeress-Game
A game code created by the Lyon group for our Basic Programming group project

*Creators:* Sanna Bashir, Geanina Verestiuc and Aidan Ward

*Course:* Basic Programming

*Study Program:* Cognitive Science and Artificial Intelligence, year 1

*Instructors:* Dr. F. Hermens and E. van Miltenburg 



# Description
This code serves as a platformer, PvE (player versus enemy) game. The code is written using the python programming language and pygames as the main library. The purpose of this game is to defeat all the enemies without the character dying. A powerup is available throughout the game. This powerup attack decreases the enemies health more than the normal player attack. This powerup is in the form of a potion and can be found across the screen. There is more than one potion, each potion gives the player one chance at a special attack.

# Requirements
*Libraries needed:*

    ○ Pygame 1.9.4
    ○ Random
    ○ Os
    ○ Sys

Python version 3.7.1 was used to create the game.

The game was tested and cleared to be working properly on versions 3.7.1, 3.6, 3.6.5, 3.3.2 of Python.

It worked on both Windows and MacOs.

Tested with the following IDE's:

    ○ Python's build-in IDLE 3.7.1
    ○ Anaconda's Spyder 3.3.2
    ○ PyCharm 3.4
    
Download python + IDLE from https://www.python.org/downloads/

Download anaconda from https://www.anaconda.com/download/#macos

To download pygame (in terminal):

    pip3 install pygame


Python's IDLE was used to create this game. 

The code works fine in Spyder _ONLY_ if you change the last sentence from 'sys.exit()' to 'exit()'. It is unknown to us why this is a requirement, but after some research, we suspect it has something to do with the implementation detail of python in IPython and CPython.

The code works in PyCharm.

# Instructions

*Goal:*
The goal is to kill all the enemies using either the attack or the powerup attack, without letting your player die. Each enemy has a health of 100. The first enemy; the zombies are the easiest to defeat. The next enemies; the orks are a little harder to defeat. The last enemy: the Desert Robot is the hardest to defeat and also has its own attack.

*Controls/operation:*
There are two ways to control the character in the game. Either using the arrow or WASD keys on the players keyboard. Each key's function is defined below.

    'return' (enter) = start game
    'esc' = escape/quit game
    'spacebar' = shoot player's attack
    'p' = pause the game
    'q' = escape/quit game

    'w' = jump
    'a' = move left
    's' = _does nothing_
    'd' = move right
    'e' = shoot player's powerup attack

    Up arrow = jump
    Left arrow = move left
    Down arrow = _does nothing_
    Right arrow = move right
    '/' = shoot player's powerup attack

*Adjusting speed of code:*
After running the code succesfully for the first time, check if the game is not too slow or fast. If it is too slow, change the FPS settings at the beginning of the code to be a little higher. If the game seems too fast, lower the FPS. Test the new setttings and settle on a FPS that suits you and your computer. (this is addressed in the report)


# Acknowledgements
We'd like to thank the following youtube channels for helping us with getting to know the pygame module:

https://www.youtube.com/channel/UCNaPQ5uLX5iIEHUCLmfAgKg

https://www.youtube.com/channel/UC4JX40jDee_tINbkjycV4Sg

https://www.youtube.com/watch?v=K5F-aGDIYaM


We'd like to thank Bo for testing our game extensively.

We'd like to thank everybody that provides free sprites and sound effects, without them this game wouldn't be what it is today.

# Reference List

_Images/sprites_

Powerup arrow:
[Flaming Arrow Productions]. (n.d.). _FIRE ARROW PNG 3_ [Image].  Retrieved from https://pngimage.net/fire-arrow-png-3

Background:
[Free Game Assets (GUI, Sprite, Tilesets)]. (2018). _Parallax Halloween 2D Game Backgrounds_ [Image]. Retrieved from https://free-game-assets.itch.io/parallax-halloween-2d-game-backgrounds

Player: 
[Free Game Assets (GUI, Sprite, Tilesets)]. (2017). _Free 2D Woman Warrior Sprite Sheets_ [Images]. Retrieved from https://free-game-assets.itch.io/free-2d-woman-warrior-sprite-sheets

Zombie:
[Free Game Assets (GUI, Sprite, Tilesets)]. (2016). _Free 2D Game Zombie Sprite_ [Images]. Retrieved from https://free-game-assets.itch.io/free-2d-game-zombie-sprite/

Orks:
[Free Game Assets (GUI, Sprite, Tilesets)]. (2017). _2D Trolls Free Sprite_ [Images]. Retrieved from https://free-game-assets.itch.io/2d-trolls-free-sprite

Desert Robot + enemy shot:
[Free Game Assets (GUI, Sprite, Tilesets)]. (2018). _Free 2D Robot Sprite_ [Images]. Retrieved from https://free-game-assets.itch.io/free-2d-robot-sprite

Potion:
[Free Game Assets (GUI, Sprite, Tilesets)]. (2016). _Free Game Icons Potions_ [Image]. Retrieved from https://free-game-assets.itch.io/free-game-icons-potions/download/eyJleHBpcmVzIjoxNTQ3NTU5MTM0LCJpZCI6MTQ1NTE1fQ%3d%3d%2e%2fmgG4VvNONaNJRnbDatB0tPNOd8%3d

Arrow:
[Free Game Assets (GUI, Sprite, Tilesets)]. (2017). _Free 2D Woman Warrior Sprite Sheets_ [Image]. Retrieved from https://free-game-assets.itch.io/free-2d-woman-warrior-sprite-sheets

Platforms/ground tile/visual stuff:
FREE GRAVEYARD PLATFORMER TILESET [Images]. (n.d.). Retrieved from https://www.gameart2d.com/free-graveyard-platformer-tileset.html


_Sound effects_

Winning sound:
[bboyjoe_15]. (2015). _Mortal Kombat sfx » You Win.mp3_ [Audio]. Retrieved from https://freesound.org/people/bboyjoe_15/sounds/321917/

Player hit:
[cabled_mess]. (2016). _Lose (Retro video game SFX) » Lose_C_03_ [Audio]. Retrieved from https://freesound.org/people/cabled_mess/sounds/350984/

Arrow shooting:
[Davidsraba]. (2016). _Shoot Sound_ [Audio]. Retrieved from https://freesound.org/people/Davidsraba/sounds/347171/

Starting sound:
[kurt]. (2011). _Voice Samples_ [Audio]. Retrieved from https://opengameart.org/content/voice-samples

Losing sound:
[Mattix]. (2018). _GAME_OVER_05_LOST_CONSCIOUSNESS.wav_ [Audio]. Retrieved from https://freesound.org/people/Mattix/sounds/435196/

Zombie hit:
[Sound of a burp] [Audio]. (n.d.). Retrieved from https://freesound.org/

Desert Robot hit:
[Sound of a monster getting hit] [Audio]. (n.d.). Retrieved from https://freesound.org/

Ork hit:
[Sound of a monster getting hit] [Audio]. (n.d.). Retrieved from https://freesound.org/

Background music:
[You're Perfect Studio]. (2018). _Spooky Dungeon_ [Audio]. Retrieved from https://opengameart.org/content/spooky-dungeon



