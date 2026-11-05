# Brick Land

A retro side-scrolling platformer that runs in the browser. It's a single HTML file with no build step and no dependencies.

All of the pixel art, music and sound effects are original. The sprites are drawn in code, and the chiptune soundtrack and effects are generated live with the Web Audio API.

## Play

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Controls

| Key | Action |
| --- | --- |
| ← → / A D | Move |
| Z / Space / ↑ | Jump (hold to jump higher) |
| X / Shift | Run |
| Enter | Start |
| P / Esc | Pause |
| M | Toggle sound |

On touch devices, on-screen buttons appear below the game.

## Features

- One long level with question blocks, breakable bricks, pipes, pits, stairs, a checkpoint, a flagpole and a castle
- Walking enemies you can stomp, and shelled enemies whose shells you can kick into other enemies
- Power-up mushroom: grow, then break bricks
- Coins (100 coins gives an extra life), score, timer and a saved high score
- Looping original theme that speeds up when time runs low, plus jingles for death, course clear and game over
