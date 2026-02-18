# Assembly: Endgame

A React-based word guessing game inspired by classic hangman mechanics, featuring dynamic state-driven UI updates, visual feedback, and accessibility-focused design.

## 🚀 Live Demo
🔗 https://assemblyendgame-manrojgill.netlify.app/

---

## 📌 Overview

Assembly: Endgame is an interactive single-page React application where users guess a hidden programming-related word letter by letter. Each incorrect guess eliminates a programming language from a visual list — when all languages are removed, the game ends. The application emphasizes dynamic rendering, user feedback, and accessibility best practices.

---

## ✨ Features

- On-screen alphabet keyboard for user input
- Dynamic word reveal as correct letters are guessed
- Visual “language elimination” system for incorrect guesses
- Contextual farewell messages when a language is lost
- Confetti celebration on win
- Game over state when all attempts are exhausted
- Restart functionality for new games
- Accessibility enhancements:
  - Screen reader-friendly status updates
  - ARIA labels for keyboard buttons
  - Live region announcements for feedback

---

## 🛠 Technical Implementation

- Built with React (functional components + hooks)
- State management for:
  - `currentWord`
  - `guessedLetters`
  - win/loss state
- Conditional rendering based on game state
- Utility functions:
  - `getRandomWord` for randomized word selection
  - `getFarewellText` for dynamic elimination messages
- UI updates dynamically based on correct and incorrect guesses
- Keyboard buttons disable after selection and visually indicate correctness