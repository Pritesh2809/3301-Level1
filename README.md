# 🦖 Dino Run – Cicada 3301² (Clue Decrypt Puzzle)

This is an advanced HTML5/JS browser game inspired by the classic Dino Run, with a Cicada 3301-style cryptographic twist. At a score of **3301**, an encrypted clue appears — your challenge is to decrypt it using the provided hint.

## Features

- **Animated gameplay**: Parallax clouds, glowing ground, enhanced dino/obstacle sprites, jump/landing particle effects, and more.
- **Dynamic Difficulty**: Difficulty increases as you approach 3301.
- **Clue Reveal**: Reach a score of 3301 to reveal the encrypted string.
- **Accessibility**: Keyboard and pointer controls, desktop-only.
- **Skip Code**: Type `skip3301` during the game to instantly reveal the clue.

## Getting Started

1. **Clone or download** this repo.
2. **Open the HTML file** in a modern desktop browser (Chrome, Edge, Firefox).
3. Play using:
   - `Space` or `↑`/tap to jump
   - `↓` or `S` to duck
   - `R` to restart

## The Puzzle

- At **score = 3301**, a Cicada-style clue appears.
- **Encrypted string:**  
  The string is obfuscated using a logical, reversible method (no Base64).
- **Hint:**  
  _"Work in reverse — untangle neighbors, then step numerals back three."_

### Decrypting the Clue

1. **Reverse the encrypted string.**
2. **Untangle neighbors** — try swapping every pair of adjacent characters.
3. **Step numerals back three** — for each digit, subtract three (e.g., `5` → `2`, `8` → `5`).  
   Non-numeric characters remain unchanged.

The clue should then be readable!

## Accessibility / Mobile

- **Mobile devices are not supported.**  
  Please use a desktop browser for the best experience.

## Copying the Clue

- Use the "📋 Copy encrypted" button to copy the clue for external decryption.

## Credits

- Inspired by [Cicada 3301](https://en.wikipedia.org/wiki/Cicada_3301) puzzle culture.
- Classic Dino Run mechanics reimagined with modern visual effects.

---

**Have fun decrypting! 🦖**
