# CRYPTFALL III — The Ossuary

A browser-based gothic zombie dungeon survival roguelite, adapted from CRYPTFALL II.

## Getting started

Upload the following to the ROOT of your existing GitHub Pages repository:

- `index.html`
- `style.css`
- `game.js`
- `assets/atlas.png`

`assets/atlas.json` is provided as an asset reference; the game embeds the sprite locations in game.js, so that file is optional for hosting.

IMPORTANT: Do not just upload `index.html`. V3 requires the accompanying CSS, JS and assets directory.

## Existing GitHub repository

At your repository, use **Add file > Upload files**. Drag in `index.html`, `style.css`, `game.js`, and the `assets` directory (from your unzipped folder) into the repository root. If GitHub’s web interface doesn’t allow overwriting existing files using upload, first delete or rename old files via commits, then upload these replacement files. Keep the `assets/atlas.png` path unchanged. If the previous game only had one `index.html`, replacing it and adding the others is sufficient.

GitHub Pages -> Settings -> Pages -> Deploy from a branch -> main / (root).

## Controls

WASD: move
Mouse: aim
Left mouse: shoot
Shift: dash
E: interact with chests, seals, shrines, exit stairs
F: healing vial
R: reload
1/2: weapons
P / Escape: pause
M: minimap reveal

## Loop

Find two ancient seals per floor, gather resources, open chests, fight the undead, and reach the locked stairs to descend. Blessings are chosen between depths. The best floor record is stored locally in the browser.

## Important notes

The game is a fully client-side project. No registration, hosting backend, or paid game assets are needed. Visual art is a new procedurally generated image atlas. The browser-game mechanics are carried over from CRYPTFALL II. This build passed a static JavaScript syntax check, but not a full interactive browser playtest in the environment used to package it.
