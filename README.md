# SecretCode Game

A tiny browser game: crack a 5-character secret code.

**Play here:** https://kwarciyk5-pixel.github.io/secret-code-game/

## The rules

- The secret is 5 characters: **4 letters (A-Z) + 1 digit (0-9)**, in a random order.
- No character in the secret repeats.
- You type 5-character guesses. Your guesses **can** repeat characters.
- After each guess you get a score `X,Y`:
  - **X** = characters that are correct **and in the right position**
  - **Y** = characters that are correct but in the **wrong position**
  - Each character in the secret is only counted once.
- You win when the score is `5,0`. Unlimited attempts.

No accounts, no tracking, works offline. Single HTML file.
