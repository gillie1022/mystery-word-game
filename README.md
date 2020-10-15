# Mystery Word

## Description

Mystery Word Game.

## Details

The flow of the game goes as follows:

1. The user chooses a level of difficulty at the beginning of the program.
   Easy mode only has words of 4-6 characters; Normal mode only has words of 6-8
   characters; Hard mode only has words of 8+ characters.

2. At the start of the game, the user knows how many letters the computer's
   word contains.

3. The user to supplies one guess (i.e. letter) per round. This letter can be
   upper or lower case. If a user enters more than one
   letter, the input is invalid and the user will be asked to try again.

4. The user will be told if their guess appears in the computer's word.

5. The partially guesssed word will be displayed, as well as letters that have not been
   guessed. For example, if the word is BOMBARD and the letters guessed are a, b,
   and d, the screen should display:

```
B _ _ B A _ D
```

A user is allowed 8 guesses. The user is reminded of how many guesses they have left
after each round.

_A user loses a guess only when they guess incorrectly._ If they guess a letter
that is in the computer's word, they do not lose a guess.

If the user guesses the same letter twice, they do not lose a guess. 

The game ends when the user constructs the full word or runs out of
guesses. If the player runs out of guesses, the word is revealed.

When a game ends, the user is asked if they want to play again. The game begins
again if they reply (y)es.
