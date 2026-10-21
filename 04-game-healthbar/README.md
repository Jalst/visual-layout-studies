# Game healthbar: four readable states

Original, self-initiated vector assets by Thomas Geoffroy, 21 October 2026. Built with Codex. This is a personal portfolio study, not paid client work, a game-engine screenshot, or a full tutorial.

The health values are 100, 50, 15 and 0 out of 100. Each state uses fill length, a number and an explicit status. The low state adds a warning triangle so colour is not the only cue. Tick marks are shown at quarters.

- Editable SVG sources: [full](health-full.svg), [half](health-half.svg), [low](health-low.svg), [empty](health-empty.svg).
- [HTML preview](index.html): four static images in a responsive grid.

Each SVG has a 420 × 104 viewBox, accessible image title/description, and no script, external images or embedded fonts. Arial is a font reference, not bundled font software. Fill percentages refer to the 314-unit interior track.

Limits: engine import, sprite slicing and in-game accessibility have not been tested. Image metadata alone is not an in-game screen-reader implementation. Keep the number and status as real game text and expose them through the engine's accessibility layer where supported. Do not infer universal accessibility or a complete HUD from these static assets.

To preview locally, serve this directory using `python3 -m http.server 8874 --bind 127.0.0.1` and open the displayed localhost address. No build step or dependencies.
