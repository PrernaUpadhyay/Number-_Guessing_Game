
# Number Guessing Game 🎲

This is a fun and interactive **Number Guessing Game** written in Python, where the player has to guess a randomly selected number between 1 and 100. The game offers two difficulty levels: **Easy** and **Hard**, each giving a limited number of attempts to guess the number correctly.

## Features

- **Random Number Generation**: The game picks a random number between 1 and 100 each time it starts.
- **Difficulty Levels**: 
  - **Easy**: The player has 10 attempts to guess the number.
  - **Hard**: The player has 5 attempts to guess the number.
- **Feedback on Guesses**: The game provides feedback after each guess, indicating whether the guess was too high or too low.
- **Victory and Defeat Conditions**: Players win if they guess the correct number within the allotted attempts; they lose if they run out of guesses.

## ASCII Art Preview

```plaintext
   _____                       _   _            _   _                 _               
  / ____|                     | | | |          | \ | |               | |              
 | |  __ _   _  ___  ___ ___  | |_| |__   ___  |  \| |_   _ _ __ ___ | |__   ___ _ __ 
 | | |_ | | | |/ _ \/ __/ __| | __| '_ \ / _ \ | . ` | | | | '_ ` _ \| '_ \ / _ \ '__|
 | |__| | |_| |  __/\__ \__ \ | |_| | | |  __/ | |\  | |_| | | | | | | |_) |  __/ |   
  \_____|\__,_|\___||___/___/  \__|_| |_|\___| |_| \_|\__,_|_| |_| |_|_.__/ \___|_|   
```

## How to Play

1. **Select Difficulty**: At the start of the game, you will be prompted to choose a difficulty level.
   - **Easy**: You get 10 attempts to guess the number.
   - **Hard**: You get 5 attempts to guess the number.
   
2. **Guess the Number**: Enter your guess, and the game will tell you if the number is **too high**, **too low**, or **correct**.

3. **Win or Lose**: 
   - If you guess the number correctly, you win the game!
   - If you run out of attempts, the game ends, and the correct number is revealed.

## Example Gameplay

```plaintext
Welcome to the Number Guessing Game!
I'm thinking of a number between 1 and 100.
Choose a difficulty. Type 'easy' or 'hard': easy
You have 10 attempts remaining to guess the number.
Make a guess: 45
Too low.
Guess again.
You have 9 attempts remaining to guess the number.
Make a guess: 70
Too high.
Guess again.
...
You got it! The answer was 58.
```



4. Follow the prompts in the terminal to play the game.

## Future Improvements

- Add a scoring system based on how many attempts were left.
- Implement more difficulty levels.
- Add an option for the player to guess a range of numbers other than 1-100.


---

Let me know if you'd like any changes or additional sections!
