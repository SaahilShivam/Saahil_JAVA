Hangman Game

Overview:
This project implements a simple Hangman game using Java Swing for the graphical user interface (GUI). The game challenges players to guess the name of a country by selecting letters. The game includes features like a graphical representation of the word to guess, letter buttons, and notifications for wins and losses.

GameWindow.java:
The GameWindow.java file is the main window of the Hangman game, extending JFrame and implementing ActionListener. It manages the game's GUI and logic.

Key Components:
Buttons for Letters: Buttons labeled A-Z to allow users to guess letters.
Labels:-
lblword: Displays the current state of the word with guessed letters and blanks.
lblmessage: Displays the message prompting the user to guess a country name.
Panels:-
keypad: Contains the letter buttons.
screen: Displays the word being guessed.
notify: Notifies the user of the game's state.

Game Logic:
startGame(): Initializes the game by selecting a random word and setting up the blanks.
actionPerformed(ActionEvent ae): Handles button clicks, updating the word display and checking for win/loss conditions.

Features:
Random Word Selection: Chooses a word from a predefined list of country names.
Letter Guessing: Updates the display with correct guesses and disables buttons after they are clicked.
Win/Loss Notification: Alerts the player if they have guessed the word correctly or lost all their chances, and offers the option to restart the game or return to the main menu.

Hangman.java:
The Hangman.java file serves as the entry point for the Hangman game. It contains the main method which initializes the game by displaying the main menu.

Key Components:
Main Method:-
Menu Initialization: Creates an instance of the Menu class and calls its addComponent() method to set up and display the main menu.

Menu.java
The Menu.java file defines the main menu for the Hangman game, extending JFrame and implementing ActionListener. It provides options to start the game, view instructions, or exit the application.

Key Components

Buttons:-
option1: Button to start the game.
option2: Button to view instructions.
option3: Button to exit the game.
Label:
name: Displays the title "HANGMAN".
Constructor:-
Initializes the buttons and label, sets the window properties like title, size, and default close operation.
Methods

addComponent():-
Sets up the layout using GridBagLayout and adds the buttons and label to the frame.
Adds action listeners to the buttons.
actionPerformed(ActionEvent e):
Handles button click events:
Play Game: Starts the game by creating an instance of GameWindow and calling startGame().
View Instructions: Displays a message dialog with the game instructions.
Exit: Exits the application.





Summary for GitHub
Hangman Game

Overview
This project implements a simple Hangman game using Java Swing for the graphical user interface (GUI). The game challenges players to guess the name of a country by selecting letters. The game includes features like a graphical representation of the word to guess, letter buttons, and notifications for wins and losses.

Files
GameWindow.java

The GameWindow.java file is the main window of the Hangman game, extending JFrame and implementing ActionListener. It manages the game's GUI and logic.

Buttons for Letters: Buttons labeled A-Z to allow users to guess letters.
Labels:
lblword: Displays the current state of the word with guessed letters and blanks.
lblmessage: Displays the message prompting the user to guess a country name.
Panels:
keypad: Contains the letter buttons.
screen: Displays the word being guessed.
notify: Notifies the user of the game's state.
Game Logic: Handles the start of the game, letter guessing, and win/loss notifications.


Hangman.java

The Hangman.java file serves as the entry point for the Hangman game. It contains the main method which initializes the game by displaying the main menu.

Main Method: Initializes the Menu class and displays the main menu.


Menu.java

The Menu.java file defines the main menu for the Hangman game, extending JFrame and implementing ActionListener. It provides options to start the game, view instructions, or exit the application.

Buttons:
option1: Button to start the game.
option2: Button to view instructions.
option3: Button to exit the game.
Label:
name: Displays the title "HANGMAN".
Methods:
addComponent(): Sets up the layout and adds components to the frame.
actionPerformed(ActionEvent e): Handles button click events for starting the game, viewing instructions, and exiting.
​​





