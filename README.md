# Game Structure
    1. Define a Game class with the following attributes:
          board: a 3x3 array to represent the game board
          current_player: a symbol (:x or :o) indicating whose turn it is
          winner: a symbol (:x or :o) or nil if the game is ongoing
    2. Initialize the Game instance with an empty board and set current_player to :x
# Game Loop
    1. Run an infinite loop until the game is won or drawn
    2. Inside the loop:
          Print the current board state
          Ask the user for their move (row and column numbers)
    3. Validate the move:
          Check if the cell is empty
          Update the board attribute accordingly
    4. Switch the current_player symbol
    5. Check for a winner:
          Horizontal, vertical, or diagonal win
          Update winner attribute if a winner is found
    6. If no winner, continue to the next iteration
# Winning Conditions
    1. Define a method won? to check for a winner
    2. Implement the winning condition checks:
          Horizontal win: check if three consecutive cells in a row contain the same symbol
          Vertical win: check if three consecutive cells in a column contain the same symbol
          Diagonal win: check if two cells on the main diagonal or two cells on the anti-diagonal contain the same symbol
# Game Over
    1. If a winner is found, print a congratulatory message and exit the game loop
    2. If the board is full and no winner is found, declare a draw and exit the game loop

# files to be included
    board
    
