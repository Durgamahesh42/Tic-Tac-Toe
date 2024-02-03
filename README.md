**Tic Tac Toe Game**

**Overview:**

This program implements a simple Tic Tac Toe game in C. The game allows two players to take turns marking spaces on a 3x3 grid until one player wins by having three of their marks in a row (horizontally, vertically, or diagonally), or the game ends in a draw.

**Files:**

1. **tic_tac_toe.c:** This file contains the source code for the Tic Tac Toe game.

2. **README.md:** This file provides instructions and information about the Tic Tac Toe game.

**How to Run:**

To run the Tic Tac Toe game:

1. Compile the source code using a C compiler. For example, you can use GCC:

   ```
   gcc -o tic_tac_toe tic_tac_toe.c
   ```

2. Execute the compiled program:

   ```
   ./tic_tac_toe
   ```

3. Follow the on-screen instructions to play the game.

**How to Play:**

1. The game starts with an empty 3x3 grid labeled with numbers from 1 to 9, representing each cell.

2. Players take turns entering their mark ('X' or 'O') into an empty cell by choosing the corresponding number.

3. The game ends when one player has three of their marks in a row (horizontally, vertically, or diagonally), or all cells are filled without a winner, resulting in a draw.

4. The player who wins the game is declared the winner, and if the game ends in a draw, it's announced as such.

**Controls:**

- Player 1: Marks the cell with 'X'.
- Player 2: Marks the cell with 'O'.
- Use the number keys (1-9) to choose the cell to mark.

**Note:**

- Ensure that you have a C compiler installed on your system to compile and run the program.
- The game resets automatically after a winner is declared or in the case of a draw.
- The program uses the `system("cls")` function to clear the screen, which may not work on all systems. If you encounter issues with screen clearing, consider using appropriate alternatives based on your operating system.
- The game doesn't have input validation, so entering non-numeric values or out-of-range numbers may lead to unexpected behavior.

**Enjoy the Game!**+
