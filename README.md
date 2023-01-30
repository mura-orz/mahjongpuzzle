# Mahjong Puzzle

Mahjong Puzzle in ES

Single file simple game

## Environment

 - Fonts of Mahjong tiles are required. (Recommend to use Chrome on Windows)
  Otherwise, you can use alternative Japanese fonts instead. Read comment in the source code.

## Usage

- Open the file using modern web browser.
- Firstly, select a tile. The tile is selected by red cursor.
- Next, select another erasable tile, which rules are explained below.
- If both the tiles can be erased, they are erased and following tiles are shifted to left-side; otherwise, if the tiles cannot be erased, nothing happens.
- To cancel a selected tile, you can click the tile again. In other words, tile selection is toggled behavior.
- Continue to erase tiles until all the tiles are gone.
- If all the tiles in a horizontal line are erased, the line is also erased and following lines are shifted above.
- If all the tiles on the green mat are erased, this game is completed. Congratulations!
- If no tile can be erased more, the game is over. 
- Press the Reset button to try another game again.

## Rules to erase tile
 
The following tiles can be erased.
- Two tiles in the same horizontal or vertical line, regardless of blanks and other tiles between both the tiles
- Two diagonal adjacent tiles

In other words, it is like movement of the Ryu, a promoted rook in Japanese Shogi.
