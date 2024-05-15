# Python Chess Engine
## Technologies
* Python 3.7.8
* pygame 2.0.1

## TODO
- [ ] Cleaning up the code - right now it is really messy.
- [ ] Using numpy arrays instead of 2d lists.
- [ ] Stalemate on 3 repeated moves or 50 moves without capture/pawn advancement.
- [ ] Menu to select player vs player/computer.
- [ ] Allow dragging pieces.
- [ ] Resolve ambiguating moves (notation).

## Instructions
1. Clone this repository.
2. Select whether you want to play versus computer, against another player locally, or watch the game of engine playing against itself by setting appropriate flags in lines 52 and 53 of `ChessMain.py`.
3. Run `ChessMain.py`.
4. Enjoy the game!

#### Sic:
* Press `z` to undo a move.
* Press `r` to reset the game.

## Further development ideas
1. Ordering the moves (ex. looking at checks and/or captures) should make the engine much quicker (because of the alpha-beta pruning).
2. Keeping track of all the possible moves in a given position, so that after a move is made the engine doesn't have to recalculate all the moves.
3. Evaluating kings placement on the board (separate in middle game and in the late game).
4. Book of openings.