
# "Where's my Teddy?" A Pico-8 retro-game

By Lydie Chaumet, Manon Leba and Marie Koscianski-Ducharlet, during our studies at [Ada Tech School](https://adatechschool.fr/)

## Project overview

After 4 weeks of initial trainig at Ada Tech School, we were assigned this first group project with a simple goal: during a 2-week sprint, create a small video game using the fantasy console Pico-8.

We chose to design a maze game in which a toddler looks for his lost teddy bear. Initially thought as a single-level game, "Where's my Teddy?" ended up having 3 levels with different game logics (simple maze for level 1, object picking for level 2, looking for an item and bringing it back to spawn point for level 3), all in limited time.

## Challenges

This was our first ever coding-project. Such fun, but very much challenging for beginners! 

We first had to understand Pico-8 functional logic, with "Draw" functions for map generation and "Update" functions for game and interactions. Then, we created graphically and functionnaly a first level; simultaneously, we worked on a timing system and on implementing the win/lose conditions in the game.

Satisfied with our first playable version, we decided to use the remaining time creating one, then two additional levels, which led us to designin and implementing a multi-level gestion system, and thus to refactoring our entire code. 

One of the biggest challenges of this project was that it is basically impossible to use GitHub on a Pico-8 project, since the graphical elements cannot be shared in code (they are hardcoded somewhere inside the Pico-8 console and quite difficult to export/import). We thus had to share our code by copy/paste, which led to difficulties when integrating whole new functionalities.


## Screenshots

Main menu 

![Main menu](Main%20menu.png)

Level 1

![Lvl1](Lvl1.png)

Level 2

![Lvl2](Lvl2.png)

Level 3

![Lvl3](Lvl3.png)
