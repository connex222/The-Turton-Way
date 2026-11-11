# CLAUDE.md - The Turton Way

Instructions for AI assistants working in this repository.

## What this is

Turton FC's coaching philosophy and tactical playbook: game principles, tactical patterns, set pieces, player profiles and the session library.

- Live: https://connex222.github.io/The-Turton-Way/ (GitHub Pages, updates automatically from `main`)
- Audience: Turton FC coaches, players and parents.

## Architecture

- **One self-contained file: `index.html`.** All CSS, JavaScript, fonts and artwork live inside it.
- State is saved in the browser's `localStorage`. Only the theme choice is saved (key `tw-theme`). Never rename an existing key without migrating the old data, or players lose their progress.

## Hard rules

- **Fully offline.** No network requests: no CDNs, no fonts or images from the internet, no analytics, no `fetch`.
- **No external dependencies.** Everything stays inside `index.html`.
- Readable in direct sunlight and in the dark (provide both light and dark themes with strong contrast).
- Works one-handed on a phone in portrait, and safe to interrupt at any moment without losing progress.
- Free to use. Do not add adverts, tracking or sign-ups.

## Project notes

- This is the club's own document. Do not change coaching content, principles or player profiles unless Shaun asks.
- Never add players' full names, photos or personal details of children.
- Use correct UK grassroots football terms.

## Working with Shaun (the owner)

- Shaun is not a programmer. Explain every step in plain English, in order, and assume no prior knowledge.
- Always return the complete `index.html`, never partial snippets or "..." placeholders.
- Use UK English.
- Before saying a change is finished, check that the file still opens with no errors in the browser console.
- Never force-push, rewrite history or rename the repository.
