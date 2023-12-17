# The Dicee Game Challenge

This project is part of the Boss Level Challenges in the "The Complete 2023 Web Development Bootcamp" by Angela Yu. The Dicee Game is a simple two-player game involving dice rolls, where the player with the higher score wins.

## Project Description

The Dicee Game project utilizes HTML, CSS, and JavaScript to create a web-based dice game. It includes the following steps:

### Step-by-Step Implementation

1. **Step 0 - Download the Skeleton Project**:
   - Download the project's starting files from [Web Development Course Resources](https://www.appbrewery.co/p/web-development-course-resources).
   - Unzip the downloaded package to access the initial project files.

2. **Step 1 - Create an External JavaScript File**:
   - Create a new JavaScript file named `index.js`.
   - Link this JavaScript file to `index.html`.

3. **Step 2 - Add Dice Images**:
   - Locate the 'images' folder in the project.
   - Add the image file `dice6.png` as the source for both `<img>` elements.

4. **Step 3 - Create a Random Number**:
   - Inside `index.js`, initialize a variable called `randomNumber1`.
   - Set the value of `randomNumber1` to a random number between 1 and 6.

5. **Step 4 - Change the `<img>` to a Random Dice**:
   - Utilize the `randomNumber1` variable to select a random dice image (`dice1.png` to `dice6.png`) for the left `<img>` element.

6. **Step 5 - Change both `<img>` Elements**:
   - Repeat the process for the right-hand side image element.

7. **Step 6 - Change the Title to Display a Winner**:
   - Change the text in the `<h1>` element to display the winner or declare a draw based on the dice values of player 1 (left) and player 2 (right).

## How to Run the Game

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/BossLevelChallenge1_TheDiceeGame.git
   ```

2. Open `index.html` in your preferred web browser.
3. Play the game by refreshing the page to see the updated dice rolls.

## Credits

This project is part of "The Complete 2023 Web Development Bootcamp" by Angela Yu.
