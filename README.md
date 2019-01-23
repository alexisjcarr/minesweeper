# Minesweeper
This is a command line implementation of MineSweeper that I made during my time in a Codecademy Intensive course.

![minesweeper game](https://raw.githubusercontent.com/alexisjcarr/minesweeper/master/lib/game.png)

To play Minesweeper, we will create instances of MineSweeperGame in command line.

For example:

In the command line, navigate to the lib directory and run `node`.

Run `.load game.js` to load the contents of this file.

Then create a Game instance and run commands like so:
```
let game = new Game(3, 3, 3); // where the Game arguments are Game(numberOfRowsOnBoard, numberOfColumnsOnBoard, numberOfBombsOnBoard)
game.playMove(0, 1); // (0,1) represents the tile in first row and second column.
game.playMove(1, 2);
```
When done run `.exit`
