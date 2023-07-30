# Hangman Game
This is a simple implementation of the classic Hangman game in C++. The program randomly selects a word from a predefined list and then allows the player to guess individual letters in an attempt to reveal the word. For every incorrect guess, a part of the hangman is drawn, and the player loses when the entire hangman is drawn.

## How to Play
* Run the program.
* The game will display a word with all its consonants replaced by underscores ("_").
* Enter a letter you want to guess.
* If the letter is part of the word, it will be revealed in its correct position.
* If the letter is not part of the word, a part of the hangman will be drawn.
* Keep guessing letters until you complete the word or the hangman is fully drawn.
* The game will end with either a victory message if you guess the word correctly or a defeat message if the hangman is fully drawn.
