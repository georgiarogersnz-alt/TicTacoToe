# 🌮 Tic Taco Toe

A taco-themed Tic Tac Toe game that runs in the browser, written in plain HTML, CSS and JavaScript with no libraries or build step.

Tacos vs. tortillas. Three in a row wins the fiesta.

## Features

- **2 Players**: two people take turns on the same device.
- **Vs Computer**: you play tacos and go first. There are two spice levels:
  - **Leve (Easy)**: the computer makes random moves.
  - **Medio (Medium)**: the computer takes a winning move or blocks yours when it sees one, but it doesn't plan ahead, so you can beat it with a fork.
  - **Picante (Hard)**: the computer looks ahead with the minimax algorithm and can never be beaten.
- Hand-drawn SVG taco and tortilla pieces, a terracotta comal board and a papel picado banner.
- A running scoreboard, highlighting for the winning line, light and dark themes, and a layout that works on phones.

## How to play

Open `index.html` in any modern browser. Everything is in that one file.

## Play it online with GitHub Pages

1. Push this repository to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*, pick the `main` branch and the `/ (root)` folder, then click **Save**.
4. After a minute the game will be live at `https://<your-username>.github.io/<repo-name>/`.
