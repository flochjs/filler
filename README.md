# Filler

![filler](resources/filler.gif)

My player is the white one ;)

## About

Filler is a game, where two players / algorithms are fighting on a map.

A virtual machine organizes the game :

- Call the players alternatively
- Give them a random piece
- On each turn, the current player has to put his piece on the map, and try to bother the ennemy. To put a piece, the player has to write his coordinates with the "Y X\n" format on the standard input (stdin).


The course of the game appears on the standard input.

The aim of the game is to put more pieces on the map than the ennemy.

## Usage
Basic usage
```
make
./resources/filler_vm -f resources/maps/map02 -p1 ./name_of_p1 -p2 ./name_of_p2
```

Visualisator usage
```
make arena
./resources/filler_vm -f resources/maps/map02 -p1 ./name_of_p1 -p2 ./name_of_p2 | ./filler_arena
```

[Project subject](resources/filler.en.pdf)

[Norme](resources/norme.en.pdf)

### Marks. 125/100
