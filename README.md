# Signal Snake

A standalone Snake game for GitHub Pages. No installation, build step, backend, or external dependencies.

## Play

- Arrow keys or WASD: steer.
- Space: start, pause, or resume.
- R: restart.
- On phones, use the direction buttons or swipe the board.
- Eat coral squares for 10 points. Avoid walls and your own body.
- Choose Chill, Classic, or Fast. Changing pace starts a fresh round.
- Personal bests are stored on your device, separately for each pace.

## Run locally

Open `index.html` in a modern browser, or run `python -m http.server 8000` in this folder and visit `http://localhost:8000`.

## Publish on GitHub Pages

1. Put `index.html` and `.nojekyll` in the root of a GitHub repository.
2. Open **Settings → Pages**.
3. Choose **Deploy from a branch**, then **main** and **/(root)**, and save.
4. Open the site URL after the Pages deployment finishes.

The game runs entirely in the browser. It does not collect or transmit player data. Clearing browser storage removes personal bests.
