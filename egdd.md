# Game Name

## Elevator Pitch

*A one sentence pitch for your game. Pretend that your were pitching your game to a executive going to the elevator. You have less than 60 Seconds. Check [this resource](http://www.gameacademy.com/perfecting-indie-games-elevator-pitch/) for more information.*

## Influences (Brief)

- Elevator Saga game - https://play.elevatorsaga.com
  - Medium: Games
  - Explanation: The game 'Elevator Saga' is the heaviest influence for our game.  We had the idea to make a game where you play by         writing coding and researched online to see if it had been done before.  This is how we discovered 'Elevator Saga', and it's             structure served as the influence for how we structured our game.
  
- Turn-based RPG games
  - Medium: Games
  - Explanation: Our game incorporates many of the fantasy elements found in classic RPG games such as Chrono Trigger and the Final         Fantasy series.

## Core Gameplay Mechanics (Brief)

- Play by programming: Gameplay will forego traditional input devices such as a mouse or gamepad and be controlled via writing code into   a live text editor.  Everything from movement, inventory management, to battle will be handled via code

- Exporation: Players are placed in a game world where they must find certain items and complete certain objectives to advance in the     game

- Equipment/Inventory: Players may equip weapons/armor they find in the game to their character, providing different benefits.  They       will also have a persistent inventory throughout the game

- Turn/timer based battle: Battle system will operate both by turn and by timer.  On the player's turn, they will have a specified         amount of time to complete a coding problem before their turn ends.  Their success of failure will determine if they are able to         attack

# Learning Aspects

## Learning Domains

Introductory javascript/typescript

## Target Audiences

- New programmers who have taken at least one introductory programming course
- Experienced programmers who are fans of RPGs

## Target Contexts

- This game would be primarily be used as practice for students already learning basic programming

## Learning Objectives

*Remember, Learning Objectives are NOT simply topics. They are statements of observable behavior that a learner can do after the learning experience. You cannot observe someone "understanding" or "knowing" something.*

- *assignment of variables*: *by the end of this game, given a variable, students will be able to assign values to that variable.*
- *iterations*: *by the end of this game, students given a task that requires several iterations, will be able to build a "for loop" to accomplish that task.  *
- *function calls*: *by the end of this game, students will be able to show how to call a function given the function*

## Prerequisite Knowledge

Prior to playing, students should be able to:
- Assign a value to a variable
- Define and use for and while loops
- Define and use if/else statements
- Call a function

## Assessment Measures

students will be given problems to solve during the game and their answers to the problem will determine how far they have gotten along in the lesson. also the enemy health and player health will display their progression.

# What sets this project apart?

- This game incorporates learning to code into a very popular genre of games, which doesn't appear to have been done before

# Player Interaction Patterns and Modes

## Player Interaction Pattern

This is a single player game.  The player will interact with the game by writing code into a a code editor within the game window

## Player Modes

- World Map: Players traverse the game map to reach the next enemy encounter.  At this phase the inventory system may be accessed
- Battle: Players engage with an enemy and complete coding challenges to get through the encounter

# Gameplay Objectives

- *Primary Objective #1*:
    - Description: write executable code under a specified time that solves the problem being asked in able to attack the enemy.
    - Alignment: this aligns with the learning objects because it gives students the ability to write code that can give them practice        and understanding with a specific topic. for example one problem could be "call function foo to attack enemy".
- *Primary Objective #2*:
    - Description: 
    - Alignment: *Describe how this aligns with one or more learning objectives*
- *etc.*

# Procedures/Actions

*Describe the control scheme and what actions a user can take in the game.*

# Rules

*What resources are available to the player that they make use of?  How does this affect gameplay? How are these resources finite?*

# Objects/Entities

*What other things are in the world that you need to design? These may or may not directly translate to actual objects and classes.*

## Core Gameplay Mechanics (Detailed)

- live coding: the controls in this game are basically how you make attacks, defend etc... players will write code in a live coding       environment via codemirror, where their code will be injected into the game to be evaluted for accuracy. they will be asked to answer   problems by writing code. once their code is submitted by a submit button, we will run a test on his code to make sure it works         properly.   
- turn based game : the player will be given a time limit. the time will depend on the diffuctulty of the problem. if the problem is     easy, they will get 5 seconds. if it is hard then 10 seconds. an example of an easy challenge will be an assignment of a variable. an   example of a difficult problem would be a for loop. if the player gets the answer right, he will be able to attack the enemy and       damage them. if the fail, the enemy will attack the player. 
- Equipment/Inventory: player will get the opportunity to pick up an item such as armor or a potion, that will help them in battle.       they will be able to pick up/ use the inventory via code. for example if a sheild presents itself in the game, the player will type     something like: pickUpShield(); which calls a function to pick up the item. the armor will act as extra health in such a way that it   does not affect     the main health of the player. if they use a health potion it will increase their health levels. they will also     have the opportunity   to pick up weapons and use them against the enemy.

    
## Feedback

if they player gets an answer correct, a small sound will be played to indicate success or progression. then another uplifting sound will be played when they attack an enemy. if they get it wrong, there will be a sound indicating they got it wrong. Then a sound will be played when the enemy attacks the player. 

longterm feedback that the player will recieve is the music getting faster. another indication they will recieve is the problems getting slighlty harder. the enemy health will also be displayed so they can keep track of their progression.

# Story and Gameplay

## Presentation of Rules

there will be some examples shown on what is expected and how to enter their answers. a small text box will be designated for advice and information on the game as well as each type of problem

## Presentation of Content

The player will be given a short problem in text on a screen. players will have to write up code to be able to solve that challenge given. They will then be shown how many they got right and wrong.

## Story (Brief)

the player will be given 3 characters to use against the enemy. the player will be given a challenge to solve. if the player gets the challenge correct, they can advance on the enemy and attack them. if they get it wrong, they player will attack one of their characters. you lose if all of your characters are defeated. you win if you defeat the enemy. 

## Storyboarding

when you start up the game, you will be welcomed to the start screen. the start screen will have a background image, a text box below it to enter code, and a box that contains buttons to inject the code you have entered. on the start screen, the way you can advance to the battle, you will have to call a function that takes you to the next scene (the battle scene). once you are in the battle scene, you will have 3 characters you can play with and one enemy player. There will be a timer. you will be timed to answer each question. if you run out of time, the enemy will attack one of your character. If you answer the question right, you will be able to advance an attack on the enemy and the enemy will not be able to attack your characters. the way you will be able to win is if you have atleast one character remaining and you have solved enough challanges to kill your enemy. then you will be shown how many questions you got right and wrong and where you can improve. 

# Assets Needed

## Aethestics

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


*Game region/phase/time are ways of designating a particularly important place in the game.*

- Music List (Ambient sound)
  - *Game region/phase/time*: *Example 1*, *Example 2*
  - *Game region/phase/time*: *Example 3*, *Example 4*
  
*Game Interactions are things that trigger SFX, like character movement, hitting a spiky enemy, collecting a coin.*

- Sound List (SFX)
  - *player attacks*: *enemy player attacks*, *user player attaks*
  - *progression*: *getting a challenge correct*, *defeating an enemy*


# Metadata

* Template created by Austin Cory Bart <acbart@udel.edu>, Mark Sheriff, Alec Markarian, and Benjamin Stanley.
* Version 0.0.3
