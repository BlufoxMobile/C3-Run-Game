# C³ FOX RUN

**Play:** https://blufoxmobile.github.io/C3-Run-Game/

A Subway-Surfers-style 3D endless runner for the Blufox Mobile team. Road-trip north from the
east-Tennessee Smokies to downtown Chicago across 12 stages, dodge the commission killers
(Exception, Fall-Off, Charge Back, Non-Usage, Retail 360), stack devices and T-sheets, and post
your COMMISSION to the shared Top-5 board.

## Controls
* **Phone:** swipe ← → to switch lanes, swipe ↑ or tap to jump.
* **Keyboard:** ← → / A D lanes · ↑ / W / Space jump · P or Esc pause · M mute.

## What's in the run
* Monsters block a lane — switch lanes. Roadblocks are low — jump them.
* Trucks: run up the yellow ramps onto the roofs (coin highways). Oncoming trucks with headlights are deadly head-on.
* Power-ups: **Magnet** (pulls every device in), **2X Cash**, **Gig Boost** (fly over everything).
* T-sheets = shields (up to 3); every 5 T-sheets = +$100.
* Level names appear on the overhead highway sign you run under — never over the road.

## Files
* `index.html` — the whole game (three.js 3D engine, UI, procedural soundtrack), built from source.
* `assets/` — painted art: `sprites/` (fox, monsters, pickups, scenery), `sky/` (12 stage skies), `ui/` (power-up icons).
* `source/c3-fox-run-3d-source.zip` — full source: `src/` modules, `build.mjs`, test tools, `CONTRACT.md`.
  Rebuild with `npm install && node build.mjs` → `dist/index.html` + `dist/assets/`.

Leaderboard: the Cloudflare Worker at `c3-fox-run.jeff-bilbrey-jb.workers.dev` (unchanged).
Dev flags: `?tier=low|med|high`, `?debug=1` (fps / draw calls), `?lb=off` (offline board).
