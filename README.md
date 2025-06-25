#   Sudoku Solver - Hacker Theme

# Creative Sudoku Grid

<table>
  <tr>
    <td style="background-color: #f0f0f0; text-align: center;">5</td>
    <td style="background-color: #f0f0f0; text-align: center;">3</td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;">7</td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
  </tr>
  <tr>
    <td style="background-color: #f0f0f0; text-align: center;">6</td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;">1</td>
    <td style="background-color: #f0f0f0; text-align: center;">9</td>
    <td style="background-color: #f0f0f0; text-align: center;">5</td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
  </tr>
  <tr>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;">9</td>
    <td style="background-color: #f0f0f0; text-align: center;">8</td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;">6</td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
  </tr>
  <tr>
    <td style="border-bottom: 2px solid black; background-color: #f0f0f0; text-align: center;"></td>
    <td style="border-bottom: 2px solid black; background-color: #f0f0f0; text-align: center;"></td>
    <td style="border-bottom: 2px solid black; background-color: #f0f0f0; text-align: center;"></td>
    <td style="border-bottom: 2px solid black; background-color: #f0f0f0; text-align: center;"></td>
    <td style="border-bottom: 2px solid black; background-color: #f0f0f0; text-align: center;"></td>
    <td style="border-bottom: 2px solid black; background-color: #f0f0f0; text-align: center;"></td>
    <td style="border-bottom: 2px solid black; background-color: #f0f0f0; text-align: center;"></td>
    <td style="border-bottom: 2px solid black; background-color: #f0f0f0; text-align: center;"></td>
    <td style="border-bottom: 2px solid black; background-color: #f0f0f0; text-align: center;"></td>
  </tr>
  <tr>
    <td style="background-color: #f0f0f0; text-align: center;">8</td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;">6</td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;">3</td>
  </tr>
  <tr>
    <td style="background-color: #f0f0f0; text-align: center;">4</td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;">8</td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;">3</td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;">1</td>
  </tr>
  <tr>
    <td style="background-color: #f0f0f0; text-align: center;">7</td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
  </tr>
  <tr>
    <td style="border-bottom: 2px solid black; background-color: #f0f0f0; text-align: center;"></td>
    <td style="border-bottom: 2px solid black; background-color: #f0f0f0; text-align: center;"></td>
    <td style="border-bottom: 2px solid black; background-color: #f0f0f0; text-align: center;"></td>
    <td style="border-bottom: 2px solid black; background-color: #f0f0f0; text-align: center;"></td>
    <td style="border-bottom: 2px solid black; background-color: #f0f0f0; text-align: center;"></td>
    <td style="border-bottom: 2px solid black; background-color: #f0f0f0; text-align: center;"></td>
    <td style="border-bottom: 2px solid black; background-color: #f0f0f0; text-align: center;"></td>
    <td style="border-bottom: 2px solid black; background-color: #f0f0f0; text-align: center;"></td>
    <td style="border-bottom: 2px solid black; background-color: #f0f0f0; text-align: center;"></td>
  </tr>
  <tr>
    <td style="background-color: #f0f0f0; text-align: center;">8</td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;">6</td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;">3</td>
  </tr>
  <tr>
    <td style="background-color: #f0f0f0; text-align: center;">4</td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;">8</td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;">3</td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;">1</td>
  </tr>
  <tr>
    <td style="background-color: #f0f0f0; text-align: center;">7</td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
    <td style="background-color: #f0f0f0; text-align: center;"></td>
  </tr>
</table>

Welcome to the **  Sudoku Solver - Hacker Theme**! This project is an advanced, neon-glowing Sudoku game with a dark hacker aesthetic. It offers a variety of difficulty levels, themes, and game options to provide a unique experience for Sudoku enthusiasts.

## Features

- **  Neon Hacker Aesthetic**: A visually appealing, hacker-inspired theme with neon glowing colors.
- **Multiple Themes**: Choose between Classic, Galaxy, and Modern themes.
- **Difficulty Levels**: Generate Sudoku puzzles with difficulty settings ranging from Easy to Expert.
- **Hint System**: Get realistic hints based on the way a human might solve the puzzle.
- **Scoring System**: Points are awarded for correct entries and deducted for incorrect inputs or when using hints.
- **Dark Mode Toggle**: Switch between dark mode and light mode for a comfortable experience.
- **No Time Limit**: Play at your own pace and enjoy the challenge.

## Getting Started

### Prerequisites

To run this project locally, you'll need:

- A modern web browser (e.g., Chrome, Firefox, Edge).

### Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/BBSRguy/Sudoku.git
   ```

2. **Navigate to the Project Directory**:

   ```bash
   cd  Sudoku
   ```

3. **Open `index.html` in Your Browser**:

   Double-click the `index.html` file or right-click and select "Open with..." to launch the game in your browser.

## How to Play

1. **New Game**: Click on the **New Game** button to generate a new Sudoku puzzle.
2. **Difficulty**: Select your desired difficulty from the dropdown (Easy, Medium, Hard, Expert).
3. **Enter Numbers**: Click on an empty cell to enter a number. Cells filled by the puzzle generator cannot be edited.
4. **Hints**: Click the **Get Hint** button to receive a hint. Note that using hints will reduce your score.
5. **Themes**: Choose between Classic, Galaxy, or Modern themes for a personalized look.
6. **Dark Mode**: Use the **Dark Mode** toggle button to switch between dark and light backgrounds.

## Game Rules

- Fill in the empty cells with numbers from 1 to 9.
- Each row, column, and 3x3 subgrid must contain all numbers from 1 to 9 without repeating.
- Entering an incorrect number will highlight the cell in red and reduce your score.

## Scoring System

- **Correct Entry**: +10 points
- **Incorrect Entry**: -5 points
- **Using a Hint**: -5 points

## Custom Themes

- **Classic Theme**: Light and simple, for a traditional Sudoku experience.
- **Galaxy Theme**: Inspired by the stars and the universe, with a dark blue gradient and purple highlights.
- **Modern Theme**: Clean, minimal, and professional with light grays and whites.

## Technologies Used

- **HTML**: Structure of the game.
- **CSS**: Styling for the hacker aesthetic, themes, and responsiveness.
- **JavaScript**: Game logic, Sudoku generation, validation, hint system, and scoring.

## Project Structure

- `index.html`: Main HTML file that includes the game interface.
- `styles.css`: Contains all CSS styles, including the dark mode and theme styles.
- `scripts.js`: JavaScript file with the logic for Sudoku generation, validation, scoring, and user interaction.

## Contributing

Feel free to fork the repository and contribute to the project by submitting pull requests. Any contributions are greatly appreciated!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the Sudoku community for inspiration and puzzle generation algorithms.
- Special shoutout to neon-glow aesthetic enthusiasts for inspiring the hacker-themed design.

Enjoy solving puzzles in style!
