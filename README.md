# Wordle (C Version)

A command-line implementation of the classic **Wordle** game, written in C.  
Guess the hidden word within a limited number of tries, using color-coded hints to guide you.

---

## Gameplay

- You’ll be given a word length (5–8 letters) when starting the game.
- You have **wordsize + 1** guesses to find the correct word.
- After each guess, letters are highlighted:
  - **Green:** Correct letter, correct position  
  - **Yellow:** Correct letter, wrong position  
  - **Gray:** Letter not in the word

## How to Start

-Compile using:
 - gcc -o wordle wordle.c
-Run:
 - ./wordle 5 (you can replace 5 with desired word lenth(5, 6, 7, 8))
