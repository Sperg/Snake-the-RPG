Snake the RPG
=============

An RPG take on the classic Snake game.

Installation
============

Make sure you have the ncurses dev pack installed.

Download the source then run 
                            "gcc -o snake main.c -lncurses > /dev/null && echo "You can run the game now." "

When it says you can run the game type "./snake" to launch.

Gameplay
========

It's still in early early alpha and being developed by one guy so expect a lot of bugs. 

You start of as a small snake in the center of the screen.
Use the arrow keys to move around. Hit 'z' to shoot. Hit the backspace key to load the pause
menu were you can switch to the gun and use health potions. (You can buy health potions at the store [also don't use the gun it's really bad.])

Same concepts of snake still apply. Eat the 's' to grow bigger, avoid the enemies (which are now snakes which you can attack and kill) and don't eat yourself (if you do you'll lose health).

If you go to the different edges of the screen you move to different parts of the map. This is represented on the minimap. 
At first the minimap is blank but you will uncover new areas as you travel. 

Throughout the game you will encounter different type of terrain. These types include: Grass - Cut it down with your sword to find coins and collectibles. Swamp - Slows down the PC and Ai. Portal - Teleports you to the next layer. Field - Speeds up the PC and Ai.

During the game you will encounter portals. Entering the portal in the center will take you down a layer. There is better loot at the shops in lower layers but the enemies get harder and the terrain harsher.

The aim of the game is to make it to the lowest layer (layer_03) and kill the boss (not yet fully implemented)

At the store you can buy potions and better weapons and at the bank you can deposit and withdraw money. (Money in the bank saves over game restarts)

There's much, much more so download the game and have an explore!
