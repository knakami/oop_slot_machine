Slot Machine Game
This is a simple text-based slot machine game implemented in Python. The game allows players to spin the slot machine, place bets on multiple lines, and check for winnings based on symbol configurations.

Game Constants
MAX_LINES: Maximum number of lines to bet on.
MAX_BET: Maximum bet amount.
MIN_BET: Minimum bet amount.
ROWS: Number of rows in the slot machine.
COLS: Number of columns in the slot machine.
Symbol Configurations
symbol_count: Dictionary containing the count of each symbol in the slot machine.
symbol_value: Dictionary representing the value of each symbol.
Functions
check_winnings(columns, lines, bet, values)

Check for winnings on the slot machine.
Returns total winnings and winning lines.
get_slot_machine_spin(rows, cols, symbols)

Generates a random spin of the slot machine.
Returns a 2D list representing the columns and rows.
print_slot_machine(columns)

Prints the current state of the slot machine.
deposit()

Handles player deposit, ensuring a valid input.
get_number_of_lines()

Gets the number of lines to bet on from the player.
get_bet()

Gets the bet amount from the player.
spin(balance)

Performs a spin, calculates winnings, and updates the player's balance.
Returns the balance change.
main()

Main game loop that orchestrates the entire game.
How to Play
Run the game by executing the main() function.
Deposit an initial amount.
Press Enter to spin or 'q' to quit during the game.
Follow the prompts to choose the number of lines and bet amount.
The slot machine will display the result, and winnings will be calculated.
Continue playing until you choose to quit or run out of money.
Enjoy the game!
