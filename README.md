# Ant Doodlebug

Ant Doodlebug is a predator-prey simulation game. The predators are doodlebugs and the prey are ants. The doodlebugs and ants will move around a grid and the doodlebugs will try to eat the ants. Doodlebugs and ants can breed (spawning more doodlebugs/ants) if they survive long enough. Doodlebugs starve if too much time passes without them having eaten an
ant. There are member variables for the number of doodlebugs and ants alive, for the number of rows and columns, the number of steps in the game, and the grid itself which is
a 2-d array of pointers to Critter objects. These pointers can point to Doodlebug or Ant objects since these classes are derived from Critter. Member functions include a default
constructor which will initialize member variables with default values, getters and setters for member variables, a play function which starts and plays the game, a printGrid function which displays the grid with the ants and doodlebugs on it, a startMenu function which displays a menu and allows the user to specify starting options, and allocGrid which dynamically allocates memory for the grid and starting Ant and Doodlebug objects.


## System Requirements

Linux, g++ 11+, GNU make

## Compilation

Use Make to compile: `$ make`

## Usage

Run executable: `$ ./main`
