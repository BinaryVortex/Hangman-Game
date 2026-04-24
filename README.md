# Hangman Game

A simple, classic Hangman game built with HTML, CSS and JavaScript.

![Gameplay Screenshot](./Screenshot%202026-04-25%20at%2003.26.33.png)

## Preview

See the screenshot above for a quick look at the game in action.

## Features

- Guess letters to discover the hidden word
- Tracks correct and incorrect guesses
- Visual hangman state for wrong attempts
- Responsive, lightweight, and easy to run locally

## How to Play

1. Open the game in your browser.
2. A hidden word will be shown as underscores.
3. Type a letter (or click letters if the UI provides buttons).
4. Correct letters will reveal their positions in the word.
5. Incorrect guesses will advance the hangman drawing.
6. You win by revealing the full word before running out of attempts.

## Installation / Run locally

No build tools required — just open the files in a browser.

Option 1 (quick):
- Double-click `index.html` to open it in your default browser.

Option 2 (recommended for consistent behavior):
- Run a simple local server and open http://localhost:8000
  - Python 3: `python -m http.server 8000`
  - Node (http-server): `npx http-server -p 8000`

## Project Structure

- index.html — main HTML file
- style.css — styles
- script.js — game logic in JavaScript
- Screenshot 2026-04-25 at 03.26.33.png — example gameplay screenshot

(Your repository may vary slightly — adjust filenames if different.)

## Tech

- HTML
- CSS
- JavaScript

## Contributing

Contributions are welcome — open an issue or submit a pull request with improvements, bug fixes, or new words and categories.

## License

This repository does not include a license file. If you want to add a license, consider adding an `LICENSE` file (for example, MIT) and mention it here.

## Author

BinaryVortex

---

If you'd like, I can:
- Add a short live demo link (GitHub Pages) and help set it up,
- Add keyboard controls and accessibility improvements,
- Create a small test suite for the game logic.
