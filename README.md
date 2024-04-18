# Tic-Tac-Toe in C

This is a simple command-line implementation of the classic TicTacToe game written in C language. It allows a player to play against the computer on the terminal.

# `Features`

- Interactive gameplay against a computer opponent.
- Simple and intuitive command-line interface.
- Basic error handling for invalid inputs.
- Win detection to determine the winner of the game.
- Ability to restart the game after completion.

# `How to use`

1.  Clone the repository to your local machine using the following command:
    ```
    git clone https://github.com/AFP17/Tic-Tac-Toe-in-C.git
    ```
2. Navigate to the project directory:
    ```
    cd Tic-Tac-Toe-in-C
    ```
3. Compile the source code using any C compiler.
    ```
    gcc TicTacToe.c -o tictactoe
    ```
4. Run the executable file:
    ```
    ./tictactoe
    ```
5. Follow the on-screen instructions to play the game against the computer.

# `How to play` 
- The game board consists of a 3x3 grid.
- You (the player) will play as 'X' and the computer will play as 'O'.
- You take the first turn and then alternate turns with the computer.
- The player who succeeds in placing three of their marks in a horizontal, vertical, or diagonal row wins the game.
- If all cells are filled without any player achieving three marks in a row, the game ends in a draw.