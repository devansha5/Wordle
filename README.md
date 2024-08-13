Wordle Clone
-----------------------------------
This is a simple Wordle clone built using Swift and UIKit. The game allows users to guess a 5-letter word within 6 attempts. The app provides feedback after each guess, indicating whether the letters are correct and in the correct position, correct but in the wrong position, or incorrect.
------------------------
Features

- Interactive Keyboard: A custom on-screen keyboard for user input.
- Guess Feedback: Each guess provides color-coded feedback:
  - Green: Correct letter in the correct position.
  - Orange: Correct letter but in the wrong position.
  - Black: Incorrect letter.
- Dynamic Word Selection: The app selects a random word from a predefined list.
- Title Display: The word "Wordle" is displayed at the top of the screen.
Demo Sequence

To demonstrate the app, you can input the following sequence of words:

1. `PLANT`
2. `TRAIL`
3. `BLURT`
4. `ALERT`
5. `ULTRA`

This sequence will guide the player towards the correct word "ULTRA".
  
<img width="426" alt="PNG image" src="https://github.com/user-attachments/assets/6701d4f7-cdc6-4995-98e9-8ec44d200056">


 Installation

To run this project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/wordle-clone.git](https://github.com/devansha5/Wordle.git

 2.   Open the project in Xcode:
cd wordle-clone
open WordleClone.xcodeproj

3. Build and run the project in the iOS Simulator or on a physical device.

Usage:

 -Start the Game: The game begins by selecting a random word from the list.
 
  -Make a Guess: Use the on-screen keyboard to input your guesses.
  
  -Receive Feedback: After each guess, the boxes will change color to reflect the accuracy of your guess.
  
  -Win or Lose: You have 6 attempts to guess the correct word. If you guess the word correctly, all boxes will turn green.
