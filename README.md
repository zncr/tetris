# Tetris

A single-file Tetris game for the browser. No build step or dependencies.

## Play

Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000   # then visit http://localhost:8000
```

## Controls

| Key | Action |
| --- | --- |
| ← / → | Move |
| ↑ / X | Rotate clockwise |
| Z | Rotate counter-clockwise |
| ↓ | Soft drop |
| Space | Hard drop |
| C | Hold piece |
| P | Pause |
| Enter | Restart after game over |

Touch buttons appear on touch devices.

Features: 7-bag randomizer, ghost piece, hold, next preview, levels and speed-up, high score saved in localStorage.

## Moon in the daytime simulation

Open `moon-daytime.html` for an interactive simulation of why the Moon is sometimes visible during the day.
