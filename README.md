# Weebshot

A dependency-free retro browser FPS prototype with raycast walls, locally drawn adult chibi enemy sprites, shotgun combat, pixel blood particles, enemy pursuit, escalating waves, health, and pause/restart.

## Play locally

Open `index.html` in a desktop browser, or serve this folder:

```sh
python3 -m http.server 8000
```

Visit http://localhost:8000. Click Enter the Arena to capture the mouse. WASD moves, mouse aims, click or Space shoots, Shift sprints, Escape pauses. Arrow keys provide an alternative to mouse aiming. Desktop keyboard and mouse required.

## Files

- `game.js`: raycasting, combat, procedural sprites, audio, and game loop.
- `style.css`: menu and HUD.
- `index.html`: browser entry point.

No downloads, dependencies, external assets, or build step required. This is an initial gameplay prototype; art, enemy navigation, levels, and weapons are intentionally simple.
