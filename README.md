# Word Guessing Game
## Attribution

The initial code structure for this project was learned from and inspired by tutorials on [Codédex](https://www.codedex.io/).
A classic word guessing game implemented in Python where players attempt to guess a hidden word by suggesting letters within a limited number of attempts.
I have added "hangman" stick figure that is changed every time the user guesses a character incorrectly.

## Features

- Random word selection from a predefined list
- Visual representation of guessed and hidden letters
- 6 attempts to guess the word correctly
- Case-insensitive input handling
- Immediate feedback on correct/incorrect guesses
- Win/lose condition messages

## How to Play

1. The game selects a random word from the word list
2. The word is displayed as underscores (e.g., "_ _ _ _ _ _" for "google")
3. Player guesses one letter at a time
4. If the letter is in the word, all instances are revealed
5. If the letter is not in the word, an attempt is deducted
6. Game continues until:
   - Player guesses all letters (win)
   - Player runs out of attempts (lose)

## Code Structure

- **Word Selection**: Randomly chooses a word from `wordList`
- **Game State**: Tracks guessed letters with `guessedWord` array
- **Game Loop**: Continues while attempts remain
- **Input Handling**: Case-insensitive letter guessing
- **Win/Lose Conditions**: Checks for complete word or exhausted attempts

## Word List

The game currently includes these words:
- amazon
- google
- nasa
- space
- techie
- peace

## Requirements

- Python 3.x
- Standard library modules: `random`

## How to Run the game 

Simply execute the Python script in any Python 3 environment:

```bash
python word_guessing_game.py
```

Enjoy playing the Word Guessing Game :)
