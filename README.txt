Hangman-Game
============

Hangman Game

Rules of the Game

Hangman is a word-guessing game. A word is chosen at random from a word bank that the player has to guess.
The player is shown the number of characters in the word but they remain masked until the player guesses that letter. 
The player has a limited number of chances to guess the correct letters.

Each round the player can either guess a single letter or try to guess the entire word. 
If the player guesses the word correctly, they win the game. If the player attempts to guess the word and fails, 
they lose the game.

If the player guesses a letter and the letter is included in the word, the letter is unmasked for 
all occurrences in the word. If the letter is not included in the word, the number of chances is decremented by one. 
If the number of chances reaches zero, the player loses the game. If the player has already guessed a letter, the number of
chances is not decremented.

SAMPLE OUTPUT OF GAME ("$>" specifies user input)

Hello, welcome to Hangman!

Word: _ _ _ _ _ _
Chances remaining: 8

Guess a single letter (a-z) or the entire word: $> a

Word: _ _ a _ _ _
Chances remaining: 8

Guess a single letter (a-z) or the entire word: $> e

Word: _ _ a _ _ e
Chances remaining: 8

Guess a single letter (a-z) or the entire word: $> o

Sorry, no o's found.

Word: _ _ a _ _ e
Chances remaining: 7

Guess a single letter (a-z) or the entire word: $> i

Sorry, no i's found.

Word: _ _ a _ _ e
Chances remaining: 6

Guess a single letter (a-z) or the entire word: $> f

Word: f _ a _ _ e
Chances remaining: 6

Guess a single letter (a-z) or the entire word: $> france

You win!

Do you want to play again? (yes/no)
$> no
