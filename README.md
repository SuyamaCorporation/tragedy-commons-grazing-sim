# Tragedy of the Commons — Grazing Simulator

A multi-round simulation illustrating Hardin's Tragedy of the Commons with a shared pasture.

## Features
- 4–6 players (you + AI agents with Greedy, Conservative, Adaptive, Random strategies)
- Shared pasture starts at 100 grass, regrows 10% per round, each cow consumes 3 grass
- Collapse mechanic: if grass goes negative, cattle are proportionally culled
- Score = cumulative cattle owned × rounds survived
- Live progress bar showing pasture health (green → yellow → red)
- Canvas line chart showing grass level and cattle counts over time
- Educational panel on Garrett Hardin and Elinor Ostrom

## How to Play
1. Open `index.html` in any modern browser
2. Select number of players (4–6) and click "New Game"
3. Each round, choose how many cattle to add (0–5) with the slider
4. Click "Add Cattle & Next Round" to proceed
5. Play all 20 rounds; final scores shown at the end

## Tech
- Static HTML/CSS/JS — no server needed
- Tailwind CSS via CDN
- No persistence (no localStorage)
