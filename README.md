# In-Play Column Trader — Racing Simulation Game (PWA)

A standalone Progressive Web App (PWA) horse racing in-running column trading simulator. No Betfair account or external API required — runs 100% client-side and offline.

## Features
1. **Career Bankroll & Stats (`localStorage`)**:
   - Start with a `£100.00` career bankroll.
   - Automatic post-race photo finish & settlement when each race finishes.
   - Tracks Career P&L, Win Rate, Best Race P&L, and recent race results history.
2. **Race Card & Distance Selection**:
   - Choose from 6 race distances and pace profiles: **5f Sprint**, **6f Handicap Sprint**, **1m Mile Classic**, **1m2f Championship**, **1m4f Middle Derby**, and **2m Stayers Cup**.
   - Generated Daily Race Card across classic venues (*Ascot*, *Cheltenham*, *Newmarket*, *York*, *Goodwood*, *Sandown*, *Kempton*, *Doncaster*, *Leopardstown*).
3. **Post-Race Results & Settlement Modal**:
   - Displays 1st / 2nd / 3rd podium finishers, your final Hedged or Unhedged Race P&L, updated Career Bankroll, and a one-tap **Next Race ▶** button.
4. **Installable Mobile PWA**:
   - Includes `manifest.json`, `sw.js` offline Service Worker, and `icon.svg` so you can install it directly to your phone's home screen in full-screen standalone portrait mode.

## Running Locally
```bash
node server.js
```
Then open `http://localhost:3000`.
