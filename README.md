🎮 Hangman: Pokémon Edition

This is a simple Hangman game written in Python, where the player must guess the name of a Pokémon. Each wrong guess costs a life, and the Hangman drawing updates until the game is won or lost.


✨ Features

- 30 Pokémon names to guess (randomly chosen each game).
- ASCII-art hangman that updates as you lose lives.
- Prevents repeated guesses from being counted again.
- Win condition when the full Pokémon name is revealed.
- Lose condition when you run out of 6 lives.


🖥️ Example Gameplay

Word to guess: _______
6 LIVES LEFT
Guess a letter: a
Word to guess: a____
5 LIVES LEFT
Guess a letter: z
You guessed z, that's not in the word. You lose a life.
  +---+
  |   |
  O   |
 /|\  |
 /    |
      |
=========


🚀 How to Run

1. Make sure you have Python 3 installed. Check with:
   python --version

2. Clone this repository:
   git clone https://github.com/YOUR-USERNAME/hangman-pokemon.git

3. Navigate into the folder:
   cd hangman-pokemon

4. Run the game:
   python hangman.py



🔮 Future Improvements

- Add more Pokémon names (from different generations).
- Add difficulty levels (easy/medium/hard).
- Add a scoring system for multiple rounds.
- Option to play again without restarting the program.