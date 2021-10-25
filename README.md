# AlbertDing8.github.io

The **Wumpus World Game** is a video game created without the use of a game engine.
The game is created using Python, PyGame, Pixelorama (pixel art/ animations), and FamiTracker (8-bit music).
All game art, code, and music was made by me within *8 hours*.
I taught myself python in the spring of 2020 and took a university course in the coding language in the autumn of 2021.

## [***Video Game Showcase Video (Wumpus World)***](https://youtu.be/DptPkKZMkds)

## [***GitHub Repository (Wumpus World)***](https://github.com/AlbertDing8/Wumpus_World/blob/66978668c3b97f88938f0c7184c71c69fbe8bd08/WumpusWorld.py)

Based off of the AI exercise "Wumpus World".

Your character is placed in a dark cave (5x5 grid). Where you are looking for gold unknowing to what resides in the unvisited squares.
There are three bottomless pits and a creature called a Wumpus that will kill you instantly.
Luckly, you are able to feel the breeze (symbol in top right corner of the square) when you are adjacent to a square with a pit, and smell the wumpus (symbol in top left corner of the square) when you are adjacent to a square with the wumpus.

Your charcter can move using the *arrow keys* and pick up gold/ leave the cave from original square with the *space bar*.

___________________________________________________________________________________________________________________________________________________________________________

The **Rogue's Life Project** was started in the summer of 2021 to create a video game without the use of a game engine.
The game is created using Python, PyGame, Pixelorama (pixel art/ animations), and FamiTracker (8-bit music).
All game assets (images, animations, music, etc.) made by me.

## [***Video Game Showcase Video (Possibly Loud)***](https://youtu.be/ZN6SAUwrTVM)

## [***GitHub Repository***](https://github.com/AlbertDing8/Rogue-s-Life/blob/dde4653a2ff248d30857ae8126208886d17d9985/Rogue'sLifeMain.py)

> ### Currently the game is able to:
> 
> - Open application
> - Close application
> - Character movement
> - Character attack
> - Use potion to heal character
> - Spawn and move monster mobs that attack the character
> - Collision damage

# ***General notes about the game and future plans:***

### **Game (TBD Title: Rogue's Life):**

- 2D overhead (zelda 1 inspired (8 bit zelda, demakes))
- Heart system (1/4 to full heart)
- Skill tree - roots: basic skills (can get all), branches: classes (one max), leaves: each class has 3 upgrades (can get all for one class)
- Go to a "shop" between stages/ dungeon
- Items: food (hp), skill points?
- Drops: money,  food (chef)
- Base stats: attack 1 heart, health 3 hearts

- 1/100 Chance to hear "*suck air though teeth* ahh" when die

### **Skill Tree Roots (can upgrade up to 5 times each):**

- Increased attack
- Increased health
- Increased movement speed
- Decreased shop prices
- Reset skill tree option

### **Classes (branches with three leaves each):**

**Necromancer (Flaming skull) - summon up to three of what you kill (electricity main attack, gain mana system)**
- Up summon amount
- Gain 50% life steal
- Main attack is now "Poison Spell" (ramping damage (cost 1/2 mana) double poison stack if already poisoned)

**Assassin - fast, high damage (x2 move speed, half health, x3 backstab damage)**
- Lose additonal half health and gain increased overall damage (x2) (backstab x5)
- Gain shadow walk (removed minion block) (to be behind enemies)
- Main attack is now "Dash" (move forward three paces (5 second cooldown)))

**Chef - chef lol (x3 damage to "ingredients", make own food i.e. new drop system)**
- Increase food potency (x2)
- Randomly (1%) "Saute" all enemies on screen to reduce the damage they do (-50%) (flash cut scene?)
- Main attack is now "Supper" (trap enemies in pots, simmer in pot for dot (no cooldown lol))

**Tank - large health (+5 hearts), low attack (gain passive low dot, lose main attack)**
- Regen (1/4 heart per 30 seconds)
- Enemies do 1/2 damage
- Main attack is now "Stun" (stops enemies from moving and attacking for 3 seconds (10 second cooldown))

**Beekeeper - constantly has 3 bees that attack what you point at, they can take damage and die, respawn after 1 min (to send bees face an enemy and attack)**
- Increase number of bees (to 5)
- Increase bee stats
- Main attack is now "Free Roam" (bees will auto attack enemies)

**Samurai**

**Sun Wukong**

### **Enemies (3 versions each stronger) (base stats):**

**Slimes**
- x1/2 move speed
- 1/2 heart damage
- 1 and 1/2 heart health

**Goblins**
- x1 move speed
- 1 heart damage
- 2 heart health

**Flying chickens/ harpies ("ingredient")**
- x2 move speed
- 1 heart damage
- 2 and 1/2 heart health

**Shark ("ingredient")**
- Water stage only
- x2 move speed
- 2 heart damage
- 3 heart health

**Minatour ("ingredient")**
- Last 2 stages
- x1 move speed
- 3 heart damage
- 5 heart health

### **Bosses:**

**Orc/ Big goblin**
- 30 heart health
- Swipe
- Jab
- Jump

**Octopus ("ingredient")**
- 75 heart health
- Tentacles moving at random intervals (get faster as time goes on)
- Move to different edges of the screen

**Big Centipeade**
- 50 heart health
- Moves through ground
- Swipe

**Lynal**
- 100 heart health
- Bow
- Big axe

**Dragon ("ingredient")**
- 150 heart health
- Fire breath (undodgeable)
- Claw swipe
- Head pound

### **Stages (one per boss, 5 waves per stage):**

**Green field (Music nice and bouncy)**
- Grass
- Green Trees

**Water (bubbly, soft)**
- Sea Floor
- Coral

**Cave (Chill and skittering of bugs)**
- Dirt
- Rock Walls

**Burnt Forest (Increase to climax)**
- Dirt
- Blackened Trees

**Castle (Noble, finale)**
- Cobble walls
- Bricked ground
