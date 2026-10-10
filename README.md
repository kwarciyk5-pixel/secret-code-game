# Crack the Code

A tiny browser game: crack a 5-character secret code.

**Play here:** https://kwarciyk5-pixel.github.io/secret-code-game/

## The rules

- Pick a mode with the ⚙ button (top right). The current mode shows beside it.
  - **4L 1N** — 4 letters (A-Z) + 1 digit (0-9), in a random order. No character repeats.
  - **Letters only** — 5 letters, no letter repeats.
  - **Letters may repeat** — 5 letters; the secret may or may not repeat letters.
- Changing mode starts a new game. The app remembers your last mode.
- You type 5-character guesses. Your guesses **can** repeat characters.
- After each guess you get a score `X,Y`:
  - **X** = characters that are correct **and in the right position**
  - **Y** = characters that are correct but in the **wrong position**
  - Each character in the secret is only counted once.
- You win when the score is `5,0`. Unlimited attempts.

No accounts, no tracking, works offline. Single HTML file.
