# Island GP — a golden-hour lap

A single-file 3D racing game in the browser. One lap around an island circuit while the
sun melts into the sea: keep the guide arrow honest and the throttle lazy about corners.

Built with **Three.js** — no build step, no install. Open `index.html` and drive.

## Play

Open `index.html` in a modern desktop browser, or play it hosted (GitHub Pages).

| Key | Action |
| --- | --- |
| `W` / `↑` | Accelerate |
| `S` / `↓` | Brake / reverse |
| `A` `D` / `←` `→` | Steer |
| `Space` | Handbrake drift |
| `C` | Toggle heli-cam |
| `R` | Reset car to track |

Clear 6 checkpoints to finish the lap. Checkpoint ticks sit top-left; the amber tick is
the one you are driving toward.

## Tech

- `index.html` — everything: markup, CSS HUD, and the game loop
- Three.js `0.160.0` loaded from unpkg through an ES module import map
- Google Fonts: Anybody
- Needs an internet connection on first load for the library and font CDN

## Run locally

Just double-click `index.html`, or serve the folder:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```
