# ToursHanoi

Default layout for "Les tours de Hanoï" game

## Goal

You must solve the [Tower of Hanoi](https://en.wikipedia.org/wiki/Tower_of_Hanoi) puzzle with a given number of disks. At the beginning of the game, all disks are placed on the left tower.

0. Left tower
1. Middle tower
2. Right tower

## Available actions

- `move <source-tower: Number> <target-tower: Number>`: Moves the disk on top of `source-tower` to the top of `target-tower`
    - `source-tower` must be an integer between 0 and 2 (inclusives)
    - `target-tower` must be an integer between 0 and 2 (inclusives)
    - The `source-tower` must not be empty
    - If the `target-tower` is not empty, the disk on the top of `source-tower` must be thinner than the one on the top of the `target-tower`

## Available inputs

The game send only one line of input being the number of disks the game contains.

## Win condition

You win the game if all the disks are placed on the right tower.
