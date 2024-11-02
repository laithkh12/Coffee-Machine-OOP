# ☕ Coffee Machine Project

Welcome to the Coffee Machine project! This project simulates a coffee vending machine where users can select drinks, pay with coins, and receive freshly brewed coffee! It’s built using Python and is organized into multiple modules, each responsible for a specific aspect of the machine's functionality.

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Components](#components)
4. [How to Run](#how-to-run)
5. [Example Usage](#example-usage)
6. [Future Enhancements](#future-enhancements)

---

## Project Overview

The Coffee Machine project emulates the operations of a coffee vending machine. It allows a user to:
- Choose from a menu of drinks (e.g., Espresso, Latte, Cappuccino).
- Check the machine’s available resources.
- Insert coins to pay for the drink.
- Receive the selected drink if resources and payment are sufficient.

The project is divided into modular components, each handling a specific functionality, making it easier to manage and expand.

---

## Features

- **Interactive CLI**: Users can select drinks, pay, or view machine reports.
- **Drink Menu**: Offers various coffee options with distinct ingredient requirements.
- **Payment Processing**: Accepts coins and calculates change.
- **Resource Management**: Tracks and updates resources (water, milk, coffee) as drinks are made.

---

## Components

1. ### `CoffeeMaker`
   - Manages the resources required to make coffee, such as water, milk, and coffee.
   - Provides functions to check resource levels, validate if resources are sufficient for a chosen drink, and deduct ingredients after making a drink.

2. ### `Menu`
   - Stores a list of available drinks, each represented as a `MenuItem`.
   - Provides functionality to display available drinks and find a specific drink by name.

3. ### `MenuItem`
   - Represents each drink item with its ingredients (water, milk, coffee) and cost.
   - Holds details about the drink’s name, ingredients required, and price.

4. ### `MoneyMachine`
   - Handles all payment-related operations.
   - Accepts coins, calculates the total inserted, verifies if the payment covers the drink cost, and handles profit tracking.

---

## How to Run

To run the Coffee Machine project:
1. Ensure all files (`coffee_maker.py`, `menu.py`, `money_machine.py`, and `main.py`) are in the same directory.
2. Run the main program:
   ```bash
   python main.py
   ```
3. Follow the on-screen prompts to:
   - Select a coffee (latte, espresso, cappuccino).
   - Insert coins to pay for the selected coffee.
   - View a resource or profit report by typing report.

## Example Usage
1. Start the program and select a coffee:
   ```bash
   What would you like? (latte/espresso/cappuccino): latte
   ```
2. Insert coins when prompted:
   ```bash
   Please insert coins.
   How many quarters?: 10
   How many dimes?: 0
   How many nickles?: 0
   How many pennies?: 0
   ```
3. If resources and payment are sufficient, enjoy your coffee:
   ```bash
   Here is your latte ☕️. Enjoy!
   ```
4. View Reports by typing:
   ```bash
   report
   ```

## Future Enhancements
- Add More Drinks: Expand the menu with additional drink options.
- Resource Refill Option: Implement a feature to refill resources.
- Detailed Payment Logs: Record and display transaction history for better tracking.


Thank you for checking out the Coffee Machine Project! We hope you enjoy exploring and running this project. ☕   
