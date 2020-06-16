# Crystal Collection Game

## Overview

Welcome to my Crystal Collector game! In this game the user must try to match the target value by clicking on the four crystals below to add points to their score. The game begins by using a random number function to generate a target number value between 19 and 120. Then another function assigns random values (between 1 and 12) to four crystal images. These values are hidden from the user but clicking on them adds their value to a score variable so the user can deduce their values with simple math. If the user matches the score variable to the target number they win. If they go over it's a loss. There are separate pop-ups for wins and losses.

Either way afterwards a function adds +1 to wins or losses, resets the game, and assigns new random numbers to the target and crystal values. In the case of there being no possible way to reach the target value with the crystal values given I've included a conditional in the crystal values function to always set one of the values to one which will eliminate any chance at an impossible to win round.

## Deployment

You can view the application by [clicking here](https://billwee.github.io/unit-4-game-crystal/)

## Technology Used

- Javascript
- HTML
- CSS
