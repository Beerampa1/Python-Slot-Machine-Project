# Python-Slot-Machine-Project
# Slot Machine Game

This is a simple text-based slot machine game implemented in Python. The game allows the player to deposit an initial amount, place bets on different lines, and spin the slot machine to check for winnings.

## Getting Started

### Prerequisites

- Python 3.x

### How to Run

1. Clone the repository or download the `slot_machine_game.py` file.
2. Open a terminal or command prompt.
3. Navigate to the directory where `slot_machine_game.py` is located.
4. Run the command:

    ```bash
    python slot_machine_game.py
    ```

## Gameplay

1. **Deposit:** The game starts by asking the player to deposit a certain amount of money.

2. **Place a Bet:** The player then chooses the number of lines to bet on and the amount to bet on each line.

3. **Spin the Slot Machine:** The player initiates a spin, and the slot machine generates random symbols for each column.

4. **Check Winnings:** The game checks for winning combinations on the selected lines and calculates the winnings.

5. **Repeat or Quit:** The player can choose to continue playing or quit the game.

## Configuration

- `Max_lines`: Maximum number of lines to bet on.
- `Max_bet`: Maximum bet amount.
- `Min_bet`: Minimum bet amount.
- `Rows`: Number of rows in the slot machine.
- `Cols`: Number of columns in the slot machine.
- `symbol_count`: Dictionary containing the count of each symbol in the slot machine.
- `symbol_value`: Dictionary containing the value of each symbol for calculating winnings.

