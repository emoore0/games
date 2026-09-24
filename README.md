# Four in a row

A Connect 4 game you play in the browser against a computer opponent, with an optional coach overlay.

Play: https://emoore0.github.io/games/

## How to play

Click a column to drop a disc, or press 1 to 7. Get four in a row across, down or diagonally.

- **Levels:** Casual, Club, Strong and Ruthless. Strong and Ruthless play the end of the game perfectly.
- **Coach overlay:** marks every threat on the board, shows which rows favour each player, and flags columns that hand the engine a win.
- **Hint:** shows the likely result of each column.
- **Undo** and **Clear board** do what they say.

Keys: H for a hint, U to undo, R to play again.

## The idea behind the coach

The player who goes first wants threats on odd rows (1, 3, 5), counting from the bottom. The player who goes second wants threats on even rows (2, 4, 6). When the board fills up, a threat on its owner's rows is usually the one that wins.

## Notes

- Everything is in one HTML file with no install. Download it and it also works offline.
- Your win, draw and loss record is saved in your own browser only.
- Built with Claude Opus 5.5.
