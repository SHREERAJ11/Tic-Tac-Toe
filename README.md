# Tic-Tac-Toe AI using Minimax Algorithm

This is a simple implementation of the Tic-Tac-Toe game where you can play against an AI powered by the Minimax algorithm.


<h3> How to Play </h3>


    Clone the repository to your local machine.
    Run the main.ipynb file.
    Follow the on-screen instructions to make your moves.

<h3> Rules </h3>


    The game is played on a 3x3 grid.
    Players take turns placing their symbol ('X' or 'O') on an empty cell.
    The first player to get three of their symbols in a row (horizontally, vertically, or diagonally) wins the game.
    If the board is filled completely without any player winning, the game ends in a draw.

<h3> Code Structure </h3>


    tic_tac_toe.py: Contains the main code for the game.
    minimax: Implementation of the Minimax algorithm for AI move calculation.
    print_board: Function to print the current state of the board.
    check_win: Function to check if a player has won.
    board_full: Function to check if the board is full.
    available_moves: Function to get available moves.
    make_move: Function to make a player's move.
    switch_player: Function to switch between players.
    evaluate: Function to evaluate the score of a board.
    minimax: Function implementing the Minimax algorithm.
    get_best_move: Function to find the best move for the AI.
    main: Main game loop.

<h3> Example Gameplay </h3>


- - -
- - -
- - -
Enter your move (0-8): 2
- - X
- - -
- - -
AI is making a move...
O - X
- - -
- - -
Enter your move (0-8): 4
O - X
- X -
- - -
AI is making a move...
O O X
- X -
- - -
Enter your move (0-8): 8
O O X
- X -
- - X
AI is making a move...
O O X
O X -
- - X
Enter your move (0-8): 6
O O X
O X -
X - X
X wins!


Enjoy playing Tic-Tac-Toe against the AI!
