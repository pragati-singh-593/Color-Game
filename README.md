# RGB Color Guessing Game

An interactive **RGB Color Guessing Game** developed using HTML, CSS, and JavaScript. The game challenges players to identify the correct colour by interpreting its RGB (Red, Green, Blue) value from a set of displayed colour options.

With two difficulty levels, Easy and Hard, the application provides an engaging way to practise colour recognition while understanding the RGB colour model.

## Live Demo

**[Play RGB Color Game](https://color-game-ps593.netlify.app/)**

## Features

- **Two Difficulty Levels:** Choose between Easy and Hard modes based on your preferred challenge.
- **RGB-Based Colour Identification:** Identify the correct colour by matching its displayed RGB value with the available colour options.
- **Dynamic Colour Generation:** Generates different colour options for each game round.
- **Interactive Gameplay:** Select a colour from the available options to check your answer.
- **Instant Feedback:** Incorrect colour selections disappear from the available options.
- **Visual Success Feedback:** Selecting the correct colour changes the entire game screen to match the target colour.
- **Restart Functionality:** Restart the game to generate a new set of colour challenges.
- **Simple User Interface:** Clean and intuitive design for an enjoyable gaming experience.

## How to Play

1. Open the game and select your preferred difficulty level.
2. Observe the RGB colour code displayed on the screen.
3. Identify the colour that matches the given RGB value.
4. Click on your selected colour from the available options.
5. If your selection is incorrect, that colour disappears, allowing you to try again.
6. If your selection is correct, the entire screen changes to the target colour.
7. Restart the game to play another round.

### Difficulty Levels

| Mode | Number of Colour Options | Description |
|---|---:|---|
| Easy | 3 | Identify the correct colour from three options. |
| Hard | 6 | Identify the correct colour from six options. |

## Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Structuring the game interface |
| CSS3 | Styling, layouts, and visual presentation |
| JavaScript (ES6) | Colour generation, game logic, event handling, and DOM manipulation |
| RGB Colour Model | Representing and identifying colours using RGB values |

## Project Structure

```text
Color-Game/
│
├── index.html        # Main game interface
├── color_game.css    # Styling and visual design
├── color_game.js     # Game logic and functionality
└── README.md         # Project documentation
```

## Getting Started

Follow these steps to run the game locally.

### Prerequisites

- A modern web browser such as Google Chrome, Firefox, or Microsoft Edge.
- A code editor such as Visual Studio Code (optional).

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/pragati-singh-593/Color-Game.git
```

**2. Navigate to the project directory**

```bash
cd Color-Game
```

**3. Run the application**

Open the `index.html` file in your preferred web browser.

Alternatively, open the project in Visual Studio Code and use the Live Server extension.

No additional dependencies or build configuration are required.

## Concepts and Implementation

This project demonstrates several fundamental JavaScript and frontend development concepts.

### 1. RGB Colour Model

The game uses the RGB colour model, where each colour is represented by three numerical values:

- **Red (R)**
- **Green (G)**
- **Blue (B)**

Each component can have a value between 0 and 255. The combination of these values determines the resulting colour.

### 2. Random Colour Generation

JavaScript is used to generate random RGB values and create different colour options for each game round.

### 3. Difficulty-Based Gameplay

The application provides two game modes with different numbers of colour choices, allowing players to experience varying levels of difficulty.

### 4. DOM Manipulation

JavaScript dynamically updates the colour options, removes incorrect selections, and changes the screen background based on the player's selection.

### 5. Event Handling

Click event listeners capture player selections and determine whether the selected colour matches the target RGB value.

## Project Objective

The primary objective of this project was to develop an interactive browser-based game while strengthening practical frontend development and JavaScript programming skills.

Key concepts explored include:

- JavaScript random number generation.
- RGB colour representation.
- Arrays and conditional statements.
- DOM manipulation.
- Event listeners and event handling.
- Dynamic CSS styling.
- Interactive game logic.

## Future Improvements

- Add a score-tracking system.
- Introduce a countdown timer for each round.
- Add more difficulty levels.
- Track the number of attempts required to find the correct colour.
- Implement a high-score leaderboard.
- Improve the interface for mobile devices.

## Author

**Pragati Singh**

- GitHub: [@pragati-singh-593](https://github.com/pragati-singh-593)
- Project Repository: [Color-Game](https://github.com/pragati-singh-593/Color-Game)

---

If you enjoyed this project, feel free to explore the repository and try the game!
