# Kenya Quiz - Geo Challenge

A geography guessing game that tests your knowledge of Kenya. Drop a pin on the map for each question — the closer you are, the more points you score!

## How it works

1. Enter your name
2. Answer 6 location questions by dropping a pin on a Leaflet map
3. Score points based on distance from the correct answer (closer = more points)
4. View your ranking on the cloud-saved leaderboard

## Tech stack

- Single-file HTML/CSS/JS (no build step)
- [Leaflet](https://leafletjs.com/) for interactive maps (CARTO tile layer)
- [Supabase](https://supabase.com/) for leaderboard persistence

## Running locally

Open `index.html` in a browser. No server required — everything runs client-side.

## Scoring

| Distance     | Points |
|--------------|--------|
| ≤ 50 km      | 1000   |
| ≤ 150 km     | 800    |
| ≤ 400 km     | 600    |
| ≤ max range  | 50-400 (scaled) |
| Beyond range | 0      |
