# ☕ Coffee Machine Project

Welcome to the Coffee Machine project! This project simulates a coffee vending machine where users can select drinks, pay with coins, and receive delicious coffee! The project consists of several components, each handling a unique part of the machine’s functionality.

## Features
- Multiple coffee options: Espresso, Latte, Cappuccino.
- Real-time ingredient tracking and reports.
- Coin-based payment system.
- Automated coffee-making process with interactive CLI.

## Components
1. [CoffeeMaker](coffee_maker.md) - Manages the coffee machine resources.
2. [Menu](menu.md) - Holds and provides drink options.
3. [MoneyMachine](money_machine.md) - Handles coin processing and payments.
4. `main.py` - The main program flow that interacts with all components.

---

## How to Run

1. Ensure all files (`coffee_maker.py`, `menu.py`, `money_machine.py`, and `main.py`) are in the same directory.
2. Run the main program:
   ```bash
   python main.py
   ```
3. Follow the prompts to select a coffee, pay, or check reports.

## Example Usage
- Select a coffee: "What would you like? (espresso/latte/cappuccino)".
- Insert coins: "Please insert coins. How many quarters?".
- Receive your coffee and enjoy!

## Individual Component Documentation
- Each component has its own README file with detailed information about its purpose, attributes, and methods.

