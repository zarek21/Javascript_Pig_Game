🐷 Pig Game – JavaScript

Pig Game is a classic dice game developed with JavaScript, HTML, and CSS, where two players compete to be the first to reach 100 points. The game uses basic logic, DOM manipulation, and browser events.

🎮 How to Play

Roll the die by clicking the “Roll Dice” button.

If you roll a number between 2 and 6, it is added to your current score.

If you roll a 1, you lose your current score and the turn switches to the other player.

Hold your score by pressing “Hold”:

Your current score is added to your total.

The turn switches to the next player.

Win the game by reaching 100 points before your opponent.

You can restart the game anytime with “New Game”.

🧩 Features

🎲 Random dice rolls using Math.random()

🔄 Dynamic player switching

🧮 Temporary and total score accumulation

🏆 Winner detection

🖼️ Dice hidden or shown depending on actions

🎯 Logic encapsulated in functions (init(), switchPlayer())

📂 Project Structure
/pig-game
│── index.html
│── style.css
│── script.js   ← (contains the game logic)
│── dice-1.png
│── dice-2.png
│── dice-3.png
│── dice-4.png
│── dice-5.png
│── dice-6.png
└── README.md

📜 Main Code (script.js)

The game is divided into several parts:

🔧 Initialization

Resets scores

Sets the active player

Hides the dice

🎲 Dice Roll Logic

Generates random numbers (1–6)

Updates the current score

Switches players when a 1 appears

📥 Hold Function

Adds current score to total

Checks if a player reached 100

Switches turn if there is no winner

🔄 New Game

Calls init() to reset everything

🚀 How to Run the Game

Download or clone the repository.

Make sure to include the dice images (dice-1.png to dice-6.png).

Open the index.html file in your browser.

You’re ready to play!

📘 Technologies Used

JavaScript (DOM, events, logic)

HTML5

CSS3
