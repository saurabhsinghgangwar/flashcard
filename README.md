# Karteikarten

A simple, mobile-friendly flashcard app for learning German vocabulary. Built as a single HTML file — no server, no accounts, no setup.

**Live app:** [saurabhsinghgangwar.github.io/flashcard](https://saurabhsinghgangwar.github.io/flashcard/)

## Quick Start

Open the link on your phone in Safari. Add your own German-English word pairs in the Words tab. Review them daily — the app remembers what you know and what you struggle with, and shows you the right words at the right time.

## How to Use on iPhone

1. Open the link in Safari
2. Tap the Share button (square with arrow)
3. Tap **Add to Home Screen**
4. It opens full-screen like a real app

## Review Modes

There are four ways to practice:

- **English → German (Type)** — See the English word, type the German translation. The app checks your spelling and marks it right or wrong.
- **English → German (Flip)** — See the English word, tap to reveal the German word. Rate yourself with Again/Hard/Good/Easy.
- **German → English (Flip)** — See the German word, tap to reveal the English meaning. Rate yourself with Again/Hard/Good/Easy.
- **Practice All (Flip)** — Go through all your cards regardless of schedule. Great for extra revision. Doesn't affect your spaced repetition progress.

## Spaced Repetition

The first three modes use spaced repetition (SM-2 algorithm). After each card, you rate how well you knew it:

- **Again** — Didn't know it. Card comes back right away.
- **Hard** — Got it, but struggled. Card comes back sooner than normal.
- **Good** — Knew it. Card moves to its next scheduled interval.
- **Easy** — Knew it instantly. Card gets pushed further out.

Words you get right keep appearing less often (1 day → 3 days → a week → a month). Words you get wrong come back quickly. Over time you spend most of your time on the words you actually need to learn.

## Features

- Add your own German-English word pairs
- Spaced repetition tracks your progress per card
- Four review modes (two flip, one typing, one practice all)
- German pronunciation — tap the speaker icon to hear any German word
- Search your word list
- Export/import backup as JSON file
- Dark theme, mobile-first design
- Works offline after first load
- All data stored locally on your device

## Your Data is Private

All your words and progress are stored in your browser's localStorage on your device. Nothing is sent to any server. Nobody else can see your data. Each person who opens the app gets their own private copy.

Use the **Export** button in Settings to back up your data. Use **Import** to restore it.

## Tips

- Set Safari downloads to "On My iPhone" (Settings → Safari → Downloads) so your backups save locally
- Start with 10-20 words and review daily — consistency beats volume
- Use the Type mode to really test yourself — it's harder than flipping but you learn faster
- The speaker icon helps with pronunciation — use it every time you see a new word
