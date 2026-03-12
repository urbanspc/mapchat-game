# mapchat-game
A game for Beyond 
# MapChat — Live World Mini Game

A real-time multiplayer map experience built entirely from scratch — no game engine, no framework, just clean vanilla HTML, CSS, and JavaScript.

Players join a shared world map, move their avatar freely, and chat live with others. Lightweight, fast, and runs entirely in the browser.

---

##  Features

- **Login & avatar selection** — pick your name and emoji character before entering the world
- **Interactive map** — a hand-crafted city layout with roads, parks, and buildings
- **Smooth movement** — click anywhere on the map to move, or use `W A S D` / arrow keys
- **Speech bubbles** — messages appear above your avatar in real time
- **Live chat sidebar** — persistent chat with timestamps and online player list
- **Simulated players** — bots wander the map and send messages to keep the world feeling alive
- **Zero dependencies** — no npm, no build step, no backend required

---

## Live Demo

[Play it here] (https://github.com/urbanspc/mapchat-game/)

---

## Tech Stack

| Layer | Tech |
|---|---|
| UI & layout | HTML5 + CSS3 (custom properties, flexbox) |
| Game logic | Vanilla JavaScript (ES6+) |
| Movement | CSS transitions + click/keyboard event listeners |
| Typography | DM Sans + DM Mono (Google Fonts) |
| Hosting | GitHub Pages |

No libraries. No frameworks. No build tools. Just the web platform.

---

## Structure

```
mapchat-game/
└── index.html    # Everything — UI, game engine, chat, bots
```

Deliberately kept as a single file for portability. Drop it anywhere and it works.

---

## Controls

| Action | Input |
|---|---|
| Move | Click on map |
| Move | `W` `A` `S` `D` or Arrow keys |
| Chat | Type in sidebar → `Enter` to send |

---

## How It Works

The map is built procedurally with CSS-positioned elements — roads, parks, and buildings are laid out using absolute positioning and styled with CSS variables for a clean, cohesive look.

Player movement uses CSS transitions with a cubic-bezier bounce curve for a satisfying feel. Bot AI runs on randomized timers — each bot independently wanders to a new position and fires off chat messages at staggered intervals, creating the illusion of a live world.

The entire state lives in memory, which keeps the architecture dead simple while still delivering a genuinely fun experience.

---

## Roadmap

This is a foundation. Planned upgrades:

- [ ] WebSocket backend for true real-time multiplayer
- [ ] Persistent user accounts
- [ ] Custom map zones and rooms
- [ ] Proximity-based chat (only see messages from nearby players)
- [ ] Mobile touch controls
- [ ] Player profiles and status messages

---

## Author

**Stephan Augustin**
CTO & Founder — [EloClouds](https://eloclouds.com) · Builder of [SynDock OS](https://eloclouds.com)

Software Engineer with a focus on full-stack web, cloud infrastructure, and product engineering. I build things end-to-end — from OS-level tooling (SynDock OS, now running on 12,000+ agencies) to consumer-facing web apps.
---

## License

MIT — free to use, fork, and build on.
