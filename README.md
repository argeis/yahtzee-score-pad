# Yahtzee Score Pad

A score card for Yahtzee played with real dice. Tap the five faces you rolled and every open box shows what it would score, or tap a box and enter the score by hand. Tracks turns for up to six players, the upper bonus, Yahtzee bonuses and the joker rule, with undo and score editing. Games are saved in the browser.

It is a single HTML page with no build step, and installs as a Progressive Web App so it works offline from the home screen.

## Run it

Open `index.html` in a browser, or serve the folder with any static file server. The service worker only registers over `http://` or `https://`.

## Install on a phone

Open the GitHub Pages URL for this repo on your phone, then:

- Android (Chrome): menu, then **Add to Home screen** or **Install app**.
- iPhone (Safari): share button, then **Add to Home Screen**.

## Files

- `index.html` – the whole app
- `manifest.webmanifest` – PWA name, colours and icons
- `sw.js` – service worker that caches the app shell for offline use
- `icons/` – app icons
