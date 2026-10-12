🎮 Java Tic-Tac-Toe with Unbeatable AI

A sleek, desktop Tic-Tac-Toe application built with Java Swing. This project features a custom graphical user interface, persistent score tracking, and an unbeatable AI opponent powered by the Minimax algorithm.

✨ Features

Unbeatable Bot: The AI uses the Minimax algorithm to calculate every possible future move. It will always win or force a draw—you can never beat it!

Alternating Roles System: Keeps gameplay fresh by rotating who goes first.

Odd Games (1, 3, 5...): You play as Red (X) and go first.

Even Games (2, 4, 6...): You play as Blue (O), and the bot plays first as Red.

Custom UI Design: A clean, modern aesthetic featuring a soft beige background, bold Crimson Red / Royal Blue game pieces, and a mint-green highlighting system for winning lines.

Session Score Tracking: Keeps a running tally of Player Wins, Bot Wins, and Ties across your session.

Controlled Game Flow: Games end cleanly, requiring a manual "Next Game" button press so you can review the final board state.



🚀 How to Run Locally

Prerequisites

Make sure you have the Java Development Kit (JDK) installed on your machine. You can verify this by opening your terminal or command prompt and typing:

java -version


Installation & Execution

Clone the repository (or download the ZIP file):

git clone https://github.com/YourUsername/your-repo-name.git
cd your-repo-name


Compile the Java file:

javac TicTacToeGUI.java


Run the application:

java TicTacToeGUI


🧠 About the AI (Minimax Algorithm)

This game implements a classic Minimax decision rule, a recursive algorithm used in artificial intelligence and game theory. The bot simulates every possible sequence of moves until the end of the game, scoring terminal states (+10 for a bot win, -10 for a player win, 0 for a tie). It then chooses the path that guarantees the highest possible outcome, assuming the player is also playing optimally. Depth calculation is included so the bot prioritizes faster wins over slower ones.

🛠️ Built With

Java (Core Game Logic)

Java Swing & AWT (Graphical User Interface)
