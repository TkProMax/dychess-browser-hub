# DYCHESS Browser Hub — v0.2

Static prototype upgraded with live public Lichess API integration.

## What is live
- Connect a Lichess username and load the public profile.
- Show current Blitz, Rapid and Bullet ratings.
- Show total games and recent public games.
- Build a browser-local leaderboard from connected players.
- Show current/upcoming Lichess tournaments.
- Link directly to Lichess profiles and tournaments.

## Important
This version does **not** use a Lichess API token. It uses public endpoints from the browser. No password or private account data is requested.

The connected-player list is stored in `localStorage` for this prototype. For a production DYCHESS platform, move player records, DYCHESS ratings, tournament results and admin controls to a server/database.

## Deploy
Upload `index.html` to Vercel as a static site, or replace the current prototype's `index.html`.
