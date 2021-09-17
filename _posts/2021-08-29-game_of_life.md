---
layout: post
title: Game of Life
---

<span class="badge js">Javascript</span>

Another project inspired by Robert Heaton's series of [Programming Projects For Advanced Beginners](https://robertheaton.com/2018/07/20/project-2-game-of-life/).

The code is written in JavaScript and uses [Node Canvas](https://github.com/Automattic/node-canvas) for image generation and [GraphicsMagick](https://aheckmann.github.io/gm//) for GIF generation. The Git repository for this project can be found [here](https://github.com/pypas/game-of-life).

[Conway's Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life) follows four simple rules:

1. Any live cell with 0 or 1 live neighbors becomes dead, because of underpopulation

2. Any live cell with 2 or 3 live neighbors stays alive, because its neighborhood is just right

3. Any live cell with more than 3 live neighbors becomes dead, because of overpopulation

4. Any dead cell with exactly 3 live neighbors becomes alive, by reproduction

An example of the Game of Life:

![game_of_life](/../img/game_of_life.gif)

-----


