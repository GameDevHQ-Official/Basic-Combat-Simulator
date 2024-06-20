# Basic Combat Simulator

## Objective

Create a simple combat simulation program in C++ that uses variables and conditionals to simulate a combat encounter between a player and an enemy.

## Requirements

### Combat Simulation

The program should:
- Ask the player for their character's name and weapon choice.
- Use variables to store the player's health and attack power.
- Use conditionals to determine the outcome of a single combat encounter.
- Display the combat results based on the player's and enemy's actions.

### Input Details

The program should collect the following inputs:
- Player's name (string)
- Weapon choice (string): Sword, Bow, or Staff

### Output

The program should display the combat actions and results, including the player's and enemy's health after the encounter.

## Steps

### 1. Set Up Project

- Create a new C++ project and set up your development environment.
- Include necessary headers (`<iostream>`, `<string>`).

### 2. Define Variables

- Define variables for player's name, weapon choice, player health, enemy health, player attack power, and enemy attack power.

### 3. Prompt User for Input

- Use `std::cin` to collect the player's name and weapon choice.

### 4. Assign Attack Power

- Use conditionals (`if`, `else if`, `else`) to set the player's attack power based on the chosen weapon.

### 5. Combat Simulation

- Use conditionals to simulate a single combat encounter, updating health values and displaying the results.

## Example User Interaction

```plaintext
Enter your character's name: Arthur
Choose your weapon (Sword, Bow, Staff): Sword

Combat Simulation:
Arthur attacks the enemy with Sword!
Enemy health: 30
The enemy attacks you back!
Arthur's health: 85

Arthur survived the attack!
```
## Submission Details

### 1. Complete the project and ensure it is bug-free.

### 2. Add the completed project to your GitHub repository.

### 3. Submit the link to your repository through your program dashboard to continue the program.

### 4. A code review will be processed once the submission is received.
