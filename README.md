# Karteikarten

A simple, mobile-friendly flashcard app for learning German vocabulary. Built as a single HTML file — no server, no accounts, no setup.

**Live app:** [saurabhsinghgangwar.github.io/flashcard](https://saurabhsinghgangwar.github.io/flashcard/)

## How It Works

Open the link on your phone in Safari, add it to your home screen, and start adding German-English word pairs. The app uses spaced repetition (SM-2 algorithm) to show you words at the right time — words you struggle with come back often, words you know well fade into the background.

## Review Modes

- **English → German (Type)** — See the English word, type the German translation. Correct answers move on, wrong answers come back soon.
- **English → German (Flip)** — See the English word, tap to reveal the German word. Rate yourself with Again/Hard/Good/Easy.
- **German → English (Flip)** — See the German word, tap to reveal the English meaning. Rate yourself with Again/Hard/Good/Easy.

## Features

- Add your own German-English word pairs
- Spaced repetition (SM-2) tracks your progress per card
- Three review modes (two flip, one typing)
- Search your word list
- Export/import backup as JSON
- Dark theme, mobile-first design
- Works offline after first load
- All data stored locally on your device (localStorage)

## Add to Home Screen (iPhone)

1. Open the link in Safari
2. Tap the Share button (square with arrow)
3. Tap **Add to Home Screen**
4. It opens full-screen like a native app

## Data & Privacy

All your words and progress are stored in your browser's localStorage. Nothing is sent to any server. Each device keeps its own separate data. Use the Export button in Settings to back up your data as a JSON file.

## Rating Buttons Explained

- **Again** — Didn't know it. Card comes back immediately.
- **Hard** — Got it, but struggled. Card comes back sooner than normal.
- **Good** — Knew it. Card moves to its next scheduled interval.
- **Easy** — Knew it instantly. Card gets pushed further out.
