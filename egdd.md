# Game Name
code warrior

## Elevator Pitch

Are you a fan of RPG games?  Well here's one with a twist.  You play the entire game by writing code.

## Influences (Brief)

- Elevator Saga game - https://play.elevatorsaga.com
  - Medium: Games
  - Explanation: The game 'Elevator Saga' is the heaviest influence for our game.  We had the idea to make a game where you play by         writing coding and researched online to see if it had been done before.  This is how we discovered 'Elevator Saga', and it's             structure served as the influence for how we structured our game.
  
- Turn-based RPG games
  - Medium: Games
  - Explanation: Our game incorporates many of the fantasy elements found in classic RPG games such as Chrono Trigger and the Final         Fantasy series.

## Core Gameplay Mechanics (Brief)

- Play by programming: Gameplay will forego traditional input devices and be controlled by writing code

- Exploration: Players are placed in a game world where they must find certain items and complete certain objectives to advance in the     game

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

- If/Else Statements: by the end of the game, students will be able to solve basic conditional tasks using an if/else statement

- Function calls: by the end of this game, students will be able to show how to call a given function and supply it with the correct       arguments needed to run

# Edit - we've decided that at a minumum, these learning objectives are necessary for the game to be playable with our new focus on incorporating more RPG elements and less chocolate covered broccoli.  Attacks and spells will be handled via function calls, and general battle mechanics will be handled via if/else statements.  Ex. Attack(ogre);  if(OgreIsUsingBigPainfulWeaponNextTurn) defend();.  I believe these mechanics will be simple to implement with the new scope.

## Prerequisite Knowledge

Prior to playing, students should be able to:
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

- Pre-battle: At this phase the inventory system may be accessed and the player can equip themselves for the upcoming battle
- Battle: Players engage with an enemy and complete coding challenges to get through the encounter

# Gameplay Objectives

- Primary Objective #1:
    - Description: write executable code to engage in battle with the enemy
    - Alignment: this aligns with the learning objectives because it gives students practice in calling functions and writing if/else         statements while playing the game
- Primary Objective #2:
    - Description: Defeat the final boss 
    - Alignment: Defeating the final boss means the player has mastered all of the coding challenges present in the game and is               therefore now a master of function calls and if/else statements

# Procedures/Actions

- The pre-battle screen will feature a number of predefined functions that are accessible to the user
  - ShowInventory(); - Bring up the inventory management window
  - CloseInventory(); - Close the inventory management window
  - Equip("characterName", "itemName"); - Equip the specified item to the specified character
  
 - The battle state of the game will feature a mixture of predefined functions and raw code
  - Attack(); - Attack the enemy with the current player character
  - Cast(); - Cast the specified spell at the enemy or player character
  - Use(); - Use the specified Item
 
# Rules

- A player has a certain amount of time to choose his attack plan for the enemy based on on-screen notifications
  and visual cues.  Ex. Enemy is preparing a strong attack!  This will let the player know that it would be wise for his next
  action to be to defend.  There will also be certain points during the battle where the player may need to satisfy some objective 
  other than simply attacking.  Ex. (if turn == 4) avoidTheRocksAboutToCrushYou

- Code that is syntactically incorrect will face a penalty (stronger enemy attack or lost turn)
  than those that are simply incorrect
  
- Weapons and armor may also have an effect on the effectiveness of attack/defense

- Coding skill required to win increases with each battle

# Objects/Entities

- Three controllable player characters in the classes of warrior, mage, and ranger
- 4 elemental themed enemies and a final boss, each in their own zone on the main map
- A main game window in the upper left corner of the screen, containing all of the game content, surrounded by UI panels including:
  - A code editor on the bottom right of the screen
  - A section containing 'submit' and 'reset' buttons to the right of the code editor, for submitting code or clearing the field
  - A text display on the right side of the screen for displaying instructions, hints, and challenges

## Core Gameplay Mechanics (Detailed)

- Play by programming: Gameplay will forego traditional input devices such as a mouse or gamepad and be controlled via writing code into   a live text editor.  Everything from movement, inventory management, to battle will be handled via code.

- Equipment/Inventory: Players may equip weapons/armor they find in the game to their character, providing different benefits.  They       will also have a persistent inventory throughout the game for storing different items needed to advance within the game.  This           inventory system will be handled via code.  Ex. Equip("charName", "itemName");

- Turn/timer based battle: Battle system will operate both by turn and by timer.  On the player's turn, they will have a specified         amount of time to complete their attack plan before their turn ends.  They will have a set list of functions they can call to
  engage with the enemy, while also satisfying certain criteria that may arise via raw code.
    
## Feedback

Successful player attack results in a loss of enemy health, while an attack against the player results in a loss of player health.  This will be visible through health bars for both the player and the enemy, which once depleted will result in either victory or defeat.  Victory results in an uplifting victory theme song being played and 'loot' being dropped by the enmy, which the player must collect and use to advance in the story.  Defeat results in a dark, gloomy melody played and restarts the current battle

# Story and Gameplay

## Presentation of Rules

A welcome screen will explain the basic structure of the game and how to play.  Each game state will feature a list of available functions that a player can call, and hints on how to interact with the game.

## Presentation of Content

Earlier stages of the game will feature some hints on the nature of the problem asked - general structure of a for loop, etc.  But the structures that will be asked are expected to be somewhat familiar before the game is played.

## Story (Brief)

An evil presence has ascended upon the land.  You must harness the power of the elements (and show off your coding skills) to bring balance back to the world.

## Storyboarding

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
    
  ## Addressing Other Games
  
  # Code Spells - This game appears to be more drag and drop / UI oriented than writing actual code, so I don't consider it to be in the   same realm of game that we are trying to make.  The comparison would be akin to designing a website via Wordpress vs. actually writing   all of the code by hand.
  
  # Adventure Land - This game is similar to the game we are trying to produce, but is much less beginner friendly.  Our game is meant to be for beginners, while it would appear Adventure Land dives into deeper concepts pf programming such as defining actual classes.  In addition the style of RPG is different.  Adventure Land appears to be more in the style of Zelda while our game is more like Final Fantasy.
  
  # Code Combat - Out of the 3 games this one is probably the most similar to what we are trying to do, but my argument would be that it   appeals to the ABSOLUTE beginner.  I played the game for around 30 minutes and the first few levels were very repetitive moveLeft()     moveRight() commands.  Not very engaging for someone that already knows a bit of code and is just looking to play a game to keep their   skills fresh.  Our game would strive to be better than this.

# Metadata

* Template created by Austin Cory Bart <acbart@udel.edu>, Mark Sheriff, Alec Markarian, and Benjamin Stanley.
* Version 0.0.3
