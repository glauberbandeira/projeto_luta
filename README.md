# Battle Arena Project

Welcome to the Battle Arena Project! This project showcases a simple yet engaging battle simulation game using HTML, CSS, and JavaScript. Below, you'll find an overview of the project's structure, logic, and key functionalities.

## Table of Contents

- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Key Components](#key-components)
  - [Character Classes](#character-classes)
  - [Stage Class](#stage-class)
  - [Log Class](#log-class)
- [How to Run](#how-to-run)
- [Future Improvements](#future-improvements)
- [Conclusion](#conclusion)

## Overview

The Battle Arena Project is a simple web-based game where two characters, a player and a monster, engage in a turn-based battle. Each character has attributes such as life, attack, and defense. The game continues until one of the characters' life points drop to zero.

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)

## Project Structure

The project consists of the following files:

- `index.html`: The main HTML file that sets up the structure of the webpage.
- `style.css`: The CSS file that styles the HTML elements.
- `script.js`: The main JavaScript file that initializes the game.
- `classes.js`: The JavaScript file that contains the classes and logic for the game.

## Key Components

### Character Classes

The `Character` class serves as the base class for all characters in the game. It defines common properties like life, attack, and defense. Other classes like `Knight`, `Sorcerer`, `LittleMonster`, and `BigMonster` inherit from `Character` and set specific values for these properties.

### Stage Class

The `Stage` class manages the game logic, including initializing the characters, handling attacks, and updating the user interface.

**Key Methods:**

- `start()`: Initializes the game and sets up event listeners for attack buttons.
- `update()`: Updates the health bars and names displayed on the screen.
- `doAttack(attacking, attacked)`: Handles the attack logic between two characters.

### Log Class

The `Log` class is responsible for maintaining a log of events that occur during the game, such as attacks and defenses. It renders these events in the HTML.

## How to Run

1. Clone the repository or download the files.
2. Open `index.html` in a web browser.
3. Click the attack buttons to engage in the battle.

## Future Improvements

- Add more character classes with unique abilities.
- Implement a more complex battle system with spells and items.
- Enhance the UI with animations and better styling.
- Implement multiplayer support.

## Conclusion

The Battle Arena Project is a great demonstration of object-oriented programming principles in JavaScript. It combines various web technologies to create an interactive and enjoyable user experience. We hope you enjoy exploring and extending this project!

---

Feel free to contact me for any questions or potential collaboration opportunities!

Thank you for your time and consideration.
