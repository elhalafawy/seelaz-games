# 🦉 Seelaz Games

A kiosk-style browser game built for **Seelaz** coffee brand.  
Single HTML file — zero dependencies, works offline.

## Games

### 🃏 Owl Memory
Match all coffee card pairs before the timer runs out.  
- 3 difficulty levels (easy / medium / hard)
- Card preview before the round starts
- Combo bonus for 4 consecutive matches

### 🌀 Owl Maze
Guide the owl through the maze to reach the coffee cup.  
- 3 difficulty levels (9×9 / 13×13 / 17×17 grid)
- Keyboard (WASD / arrows), D-pad, and touch/swipe support
- Shortest-path scoring via BFS

## Features
- Full Arabic / English language switching
- Speed + efficiency scoring (max 1000 pts)
- 3-star rating system
- Discount codes on 3-star wins (configurable %)
- High score saved in localStorage
- Web Audio API sound effects
- Confetti animation on win
- Zero external dependencies (except Google Fonts)

## Usage
Open `index.html` in any modern browser — no server needed.

## Configuration
All settings are in the `CFG` object at the top of the `<script>` block inside `index.html`:
- Brand name, website, taglines
- Time limits per game & difficulty
- Pair counts and preview durations (memory)
- Maze grid sizes
- Discount percentages
- Scoring weights

---
Built with ❤️ for Seelaz Coffee.
