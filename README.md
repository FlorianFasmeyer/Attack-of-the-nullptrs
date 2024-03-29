# Attack of the nullptrs

Attack of the nullptrs is a game created on the 22nd of January 2017 by Guillaume Noguera, Florian E. Fasmeyer, and Cédric Pahud. The game was developed as part of the C++ P2 project during our 2nd year of Computer Science.

We were instructed to create a simple desktop application with buttons and visuals using C++'s famous Qt framework. We complied with the requirements...

![A few buttons to justify our Qt project.](https://github.com/FlorianFasmeyer/Attack-of-the-nullptrs/blob/main/imgs/buttons.png)

... and made a whole game out of it!

![A picture of our ginger hero. Showcases weighted jumps and animations.](https://github.com/FlorianFasmeyer/Attack-of-the-nullptrs/blob/main/imgs/ginger-hero.gif)

![Picture of a nasty Nullptr intended on eating you](https://github.com/FlorianFasmeyer/Attack-of-the-nullptrs/blob/main/imgs/nullptr.gif)

[Listen to that music! (made by Guillaume Noguera)](https://github.com/FlorianFasmeyer/Attack-of-the-nullptrs/blob/main/pouletjetemetslefeu.mp3)

We created our own game engine and hand-made everything:

* Collisions
* Physics
* Procedural Cave Generation
* Enemy Behaviors
* Health System
* Dynamic Player Camera
* Weighted Jumps Controls
* Animation Engine
* Pixel-Art Visuals
* 8-bit Music

This game includes:

* A stylish, ginger-mustached hero with a cowboy hat
* Null Pointers trying to hunt you through the caves
* Two doors delimiting the entry and exit points of a level
* Thrilling music

[Google Doc Report (in French)](https://docs.google.com/document/d/1VTcLV2P8HV6U8FLeqMVOvjNYdaXF8jmdN7vjtiWAbsg/edit?usp=sharing)

# How to play
1. Download everything in the Attack of the nullptrs folder
2. Run AttackOfTheNullptrs.exe
3. Use arrow keypads to move left, right and jump <- ^ ->
4. Hold the up key longer to jump higher. Smaller jumps can allow you to go through very precise holes without touching the ceiling
5. Press [SPACE] to start digging. Aim where you dig with the arrow keypads
6. Get from the red door (upper left) to the blue door (lower right)
7. After each new rounds, new nullptrs will spawn. nullptrs never disappear, they are, after all, nullptrs!
8. Play enough rounds to crash your computer by generating too many nullptrs
9. Low-end computers will make "winning the game" easier. The end screen is just an out-of-memory error
