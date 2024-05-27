# connect-4Game
Running the Game
To run the game, follow these steps:

Save your code in a file named main.py.
Open a terminal or command prompt and navigate to the directory where the file is saved.
Run the following command:
bash
Копировать код
python main.py
Playing the Game
At the start of the game, you will be prompted to choose between two modes:

Single Player mode (against AI)
Two Player mode (against another human)
Single Player Mode
Press 1 for Single Player mode.
You will play with red discs, and the AI will play with yellow discs.
To place a disc, move the mouse over the column where you want to drop the disc and click.
Two Player Mode
Press 2 for Two Player mode.
The first player will play with red discs, and the second player will play with yellow discs.
To place a disc, move the mouse over the column where you want to drop the disc and click.
Game Rules
Players take turns dropping discs into the columns.
The goal is to connect four of your discs in a row, either horizontally, vertically, or diagonally.
The first player to connect four discs wins the game.
Code Structure
create_board(): Creates an empty board.
drop_piece(board, row, col, piece): Adds a disc to the board.
is_valid_location(board, col): Checks if the column is valid (not full).
get_next_open_row(board, col): Finds the next open row in the column.
winning_move(board, piece): Checks for a winning move.
draw_board(board): Draws the game board.
evaluate_window(window, piece): Evaluates a window of four locations for scoring.
score_position(board, piece): Scores the current board position.
is_terminal_node(board): Checks if the game is over (win or draw).
minimax(board, depth, alpha, beta, maximizing_player): Minimax algorithm with alpha-beta pruning.
get_valid_locations(board): Gets all valid columns for a move.
end_game(): Ends the game.
draw_menu(): Draws the initial menu.
update_move_display(move_time=None): Updates the display with move counts and times.
