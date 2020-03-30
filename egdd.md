# Game Name
code warrior

## Elevator Pitch

picture a game where you can code to play. there are no moves with buttons or mouse, but rather write code to control the game.
this game has an rpg design and a fantasy theme to it. the game can be won by getting enough challenges correct to defeat the enemy player. This game will help players improve their coding abilities for some concepts. 

## Influences (Brief)

- Elevator Saga game - https://play.elevatorsaga.com
  - Medium: Games
  - Explanation: The game 'Elevator Saga' is the heaviest influence for our game.  We had the idea to make a game where you play by         writing coding and researched online to see if it had been done before.  This is how we discovered 'Elevator Saga', and it's             structure served as the influence for how we structured our game.
  
- Turn-based RPG games
  - Medium: Games
  - Explanation: Our game incorporates many of the fantasy elements found in classic RPG games such as Chrono Trigger and the Final         Fantasy series.

## Core Gameplay Mechanics (Brief)

- Play by programming: Gameplay will forego traditional input devices and be controlled by writing code

- Exporation: Players are placed in a game world where they must find certain items and complete certain objectives to advance in the     game

- Equipment/Inventory: Equippable weapons/armor are found in the game and managed through an inventory system

- Turn/timer based battle:  Turn-based battle featuring timed coding challenges

# Learning Aspects

## Learning Domains

Introductory javascript/Typescript

## Target Audiences

- New programmers who have taken at least one introductory programming course
- Experienced programmers who are fans of RPGs

## Target Contexts

- This game would be primarily be used as practice for students already learning basic programming

## Learning Objectives

- Variable assignment: by the end of the game, given a variable, students will be able to assign values of the correct type to it with     100% accuracy

- Loops: by the end of the game, students will be able to solve basic tasks iteratively with a for or while loop

- If/Else Statements: by the end of the game, students will be able to solve basic conditional tasks using an if/else statement

- Function calls: by the end of this game, students will be able to show how to call a given function and supply it with the correct       arguments needed to run

## Prerequisite Knowledge

Prior to playing, students should be able to:
- Assign a value to a variable
- Define and use for and while loops
- Define and use if/else statements
- Call a function

## Assessment Measures

A timed assessment will be distributed before and after the game featuring problems similar to those faced during gameplay

# What sets this project apart?

- This game incorporates learning to code into a very popular genre of games, which doesn't appear to have been done before
- The game is a learning tool, but also strives to be a game that is fun to play

# Player Interaction Patterns and Modes

## Player Interaction Pattern

This is a single player game.  The player will interact with the game by writing code into a a code editor within the game window

## Player Modes

- World Map: Players traverse the game map to reach the next enemy encounter.  At this phase the inventory system may be accessed
- Battle: Players engage with an enemy and complete coding challenges to get through the encounter

# Gameplay Objectives

- Primary Objective #1:
    - Description: write executable code under a specified time that solves the problem being asked in able to attack the enemy.
    - Alignment: this aligns with the learning objects because it gives students the ability to write code that can give them practice        and understanding with a specific topic. for example one problem could be "call function foo to attack enemy".
- Primary Objective #2:
    - Description: Defeat the final boss 
    - Alignment: Defeating the final boss means the player has mastered all of the coding challenges present in the game and is               therefore now a master of for loops, function calls, and variable assignment

# Procedures/Actions

- The main game map will feature a number of predefined functions that are accessible to the user
  - Move("location"); - Move the player party to the specified location on the map
  - ShowInventory(); - Bring up the inventory management window
  - CloseInventory(); - Close the inventory management window
  - Equip("characterName", "itemName"); - Equip the specified item to the specified character
  
 - The battle state of the game will feature a mixture of predefined functions and raw code
  - Attack(); - Attack the enemy with the current player character
 
# Rules

- A player has a certain amount of time to answer a coding challenge displayed on screen

- Answers that are syntactically incorrect will face a harsher penalty (stronger enemy attack)
  than those that are simply incorrect
  
- Challenges that are deemed to be more challenging (for loop vs assignment) will provide a greater
  benefit to the player (stronger player attack)
  
- Weapons and armor may also have an effect on the effectiveness of attack/defense

- Coding challenges become more difficult with each battle

# Objects/Entities

- Three controllable player characters in the classes of warrior, mage, and ranger
- 4 elemental themed enemies and a final boss, each in their own zone on the main map
- A main game window in the upper left corner of the screen, containing all of the game content, surrounded by UI panels including:
  - A code editor on the bottom right of the screen
  - A section containing 'submit' and 'reset' buttons to the right of the code editor, for submitting code or clearing the field
  - A text display on the right side of the screen for displaying instructions, hints, and and challenges

## Core Gameplay Mechanics (Detailed)

- Play by programming: Gameplay will forego traditional input devices such as a mouse or gamepad and be controlled via writing code into   a live text editor.  Everything from movement, inventory management, to battle will be handled via code.

- Exporation: Players are placed in a game world where they must find certain items and complete certain objectives to advance in the     game.  The world map will be divided into different elemental 'zones' where each enemy has an item that is necessary to defeat the       final boss.

- Equipment/Inventory: Players may equip weapons/armor they find in the game to their character, providing different benefits.  They       will also have a persistent inventory throughout the game for storing different items needed to advance within the game.  This           inventory system will be handled via code.  Ex. Equip("charName", "itemName");

- Turn/timer based battle: Battle system will operate both by turn and by timer.  On the player's turn, they will have a specified         amount of time to complete a coding problem before their turn ends.  Their success of failure will determine if they are able to         attack, or whether the enemy attacks them.  Coding challenges will consist of things like setting a value to a variable, calling a       pre-defined function, or performing an action within a for loop (an incredibly high count of say, 1000 can be used to ensure a loop     must be utilized)
    
## Feedback

On successful completion of a coding a challenge, the player will be free to attack the enemy - bringing them closer to victory.  Each incorrect answer will bring the player closer to defeat.  This will be visible through health bars for both the player and the enemy, which once depleted will result in either victory or defeat.  Victory results in an uplifting victory theme song being played and 'loot' being dropped by the enmy, which the player must collect and use to advance in the story.  Defeat results in a dark, gloomy melody played and restarts the current battle

# Story and Gameplay

## Presentation of Rules

A welcome screen will show explain the basic structure of the game and how to play.  Each game state will feature a list of available functions that a player can call, and hints on how to interact with the game.

## Presentation of Content

Earlier stages of the game will feature some hints on the nature of the problem asked - general structure of a for loop, etc.  But the structures that will be asked are expected to be somewhat familiar before the game is played.

## Story (Brief)

the player will be given 3 characters to use against the enemy. the player will be given a challenge to solve. if the player gets the challenge correct, they can advance on the enemy and attack them. if they get it wrong, they player will attack one of their characters. you lose if all of your characters are defeated. you win if you defeat the enemy. 

## Storyboarding

when you start up the game, you will be welcomed to the start screen. the start screen will have a background image, a text box below it to enter code, and a box that contains buttons to inject the code you have entered. on the start screen, the way you can advance to the battle, you will have to call a function that takes you to the next scene (the battle scene). once you are in the battle scene, you will have 3 characters you can play with and one enemy player. There will be a timer. you will be timed to answer each question. if you run out of time, the enemy will attack one of your character. If you answer the question right, you will be able to advance an attack on the enemy and the enemy will not be able to attack your characters. the way you will be able to win is if you have atleast one character remaining and you have solved enough challanges to kill your enemy. then you will be shown how many questions you got right and wrong and where you can improve. 

# Assets Needed

## Aethestics

The aesthetics should be reminiscent of old-school 2D RPG games in the style of Chrono Trigger, Final Fantasy, Dragon Warrior, etc.  A colorful game world with elemental themed zones.  Mild combat, no blood and gore.  Somewhat lightheartedly styled characters.

## Graphical

- Characters List
  - Warrior: one of the playable characters for the player
  - Mage: one of the playable characters for the player
  - Ranger: one of the playable characters for the player
  - Earth enemy: The enemy at the earth element stage
  - Water enemy: The enemy at the water element stage
  - Ice enemy: The enemy at the ice element stage
  - Fire enemy: The enemy at the fire element stage
  - Final boss: The final boss that completes the game
  
- Textures:
  - Icons for weapons/armor and other inventory items

- Environment Art/Textures:
  - World Map: A world map that clearly identifies the region the player is in.  Lava/volcanoes for fire, oceans for water, tall             mountains and trees for earth, snow for ice
  - Fire zone: A background featuring red/organge lava and molten rock
  - Ice zone: A background featuring lots snow/ice.  White/light blue themed
  - Water zone: A background that is underwater or coastal
  - Earth zone: A background featuring mountains and trees.  Lots of brown/green

## Audio

- Music List (Ambient sound)
  - loading screen/start screen: calm flowing music
  - battle scene: exciting music to get the player going.

- Sound List (SFX)
  - battle: 
    - attack sounds
    - magic sounds
  - progression: 
    - player defeat music
    - player victory music

# Metadata

* Template created by Austin Cory Bart <acbart@udel.edu>, Mark Sheriff, Alec Markarian, and Benjamin Stanley.
* Version 0.0.3
