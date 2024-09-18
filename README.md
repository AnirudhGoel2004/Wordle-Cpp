# Wordle (C++ Terminal Version)

A terminal-based implementation of the popular Wordle game where players have 6 attempts to guess a random 5-letter word.

## Features

- **Random Word Generation**: A random 5-letter word is selected from a predefined list.
- **Color-coded Feedback**:
  - **Green** for correct letters in the correct position.
  - **Yellow** for correct letters but in the wrong position.
  - **Gray** for incorrect letters.
- **Grid Layout**: Each guess is displayed in a formatted grid with dashed lines.
- **Input Validation**: Ensures only valid 5-letter English words are accepted.

## How to Compile

1. Open a terminal and navigate to the directory with `wordle.cpp` and `valid-wordle-words.txt`.
2. Compile using:
    ```bash
    g++ -std=c++11 wordle.cpp -o wordle
    ```
3. Run the program:
    ```bash
    ./wordle
    ```

## How to Play

1. You have **6 attempts** to guess the correct 5-letter word.
2. After each guess:
   - Letters in the correct position will be **green**.
   - Letters in the wrong position will be **yellow**.
   - Incorrect letters will be **gray**.
3. Keep guessing until you find the word or run out of attempts. If unsuccessful, the game will reveal the correct word.
