# Slot Machine Game

This is a simple text-based slot machine game implemented in Python. The game allows players to spin the slot machine, place bets on multiple lines, and check for winnings based on symbol configurations.

## Game Constants
- `MAX_LINES`: Maximum number of lines to bet on.
- `MAX_BET`: Maximum bet amount.
- `MIN_BET`: Minimum bet amount.
- `ROWS`: Number of rows in the slot machine.
- `COLS`: Number of columns in the slot machine.

## Symbol Configurations
- `symbol_count`: Dictionary containing the count of each symbol in the slot machine.
- `symbol_value`: Dictionary representing the value of each symbol.

## Functions
1. **`check_winnings(columns, lines, bet, values)`**
   - Check for winnings on the slot machine.
   - Returns total winnings and winning lines.

2. **`get_slot_machine_spin(rows, cols, symbols)`**
   - Generates a random spin of the slot machine.
   - Returns a 2D list representing the columns and rows.

3. **`print_slot_machine(columns)`**
   - Prints the current state of the slot machine.

4. **`deposit()`**
   - Handles player deposit, ensuring a valid input.

5. **`get_number_of_lines()`**
   - Gets the number of lines to bet on from the player.

6. **`get_bet()`**
   - Gets the bet amount from the player.

7. **`spin(balance)`**
   - Performs a spin, calculates winnings, and updates the player's balance.
   - Returns the balance change.

8. **`main()`**
   - Main game loop that orchestrates the entire game.

## How to Play
1. Run the game by executing the `main()` function.
2. Deposit an initial amount.
3. Press Enter to spin or 'q' to quit during the game.
4. Follow the prompts to choose the number of lines and bet amount.
5. The slot machine will display the result, and winnings will be calculated.
6. Continue playing until you choose to quit or run out of money.

Enjoy the game!
