# Spotify Tournament-Style Rating App

## Description
This project is a web application that allows users to select a Spotify playlist and engage in a tournament-style song rating game. Users compare songs two at a time, selecting their favorites, until a final winner is determined. The goal is to create a fun way to explore and rank songs from a personal playlist.

## Features
- **Spotify Authorization**: Log in with your Spotify account to access your playlists.
- **Playlist Selection**: Choose any playlist from your Spotify account to use in the tournament.
- **Tournament Rating**: Songs are displayed in pairs for users to compare and select their favorite. The process continues until one song is declared the winner.
- **Undo Option**: Users can undo their last selection if they change their mind.
- **Back Button**: Allows users to return to the playlist selection page.

## How It Works
1. **Authorization**: Users log in through Spotify's authorization page to grant the app access to their playlists.
2. **Playlist Selection**: After authorization, users select a playlist from their Spotify account.
3. **Tournament**: Songs from the selected playlist are paired up for comparison. The user picks their favorite song from each pair.
4. **Winner**: The app declares a final winner once the tournament ends.

## Current Limitations
- **Incomplete Rankings**: Only songs that were selected appear in the final rankings. Songs that were never chosen are omitted.
- **Duplicates**: The same song may appear multiple times in the final rankings if selected multiple times.
- **Restart Functionality**: Restarting a tournament does not use the full playlist; only songs from the final rankings are available.

## Planned Features
1. **Complete Rankings**: Display a full ranking of all songs, including those never selected during the tournament.
2. **Randomized Matchups and Seed-Based Pairings**: Pair songs based on their Spotify popularity or listening data while adding randomness to the matchups.
3. **Track History**: Allow users to review past matchups and selections.
4. **Multi-Round Tournaments**: Add options for double-elimination and round-robin tournaments.
5. **Song Previews**: Enable users to play short previews of songs directly in the app.
6. **Enhanced Error Handling**: Improve error messages and handling for smoother user experience.

## How to Use
1. Clone or download this repository.
2. Host the files locally or through a web server (e.g., GitHub Pages).
3. Open `index.html` in a browser.
4. Log in to your Spotify account to authorize the app.
5. Select a playlist and start the tournament.

## Future Plans
These updates aim to improve functionality, usability, and overall user experience. Contributions and feedback are welcome to help bring these features to life!
