# The Broken Oath — Web Mock

A browser-first mock of the **First Videogame** prototype delivered as a small static-style Node web app. The source ZIP in Dropbox is a Godot 4.x RTS prototype; this repo deliberately does **not** ship the Godot project unchanged. Instead it recreates the useful browser-facing slice: the Sable Vale map, Alder League vs. Flint Crown, hillforts, iron sites, gatherers, spearmen, selection, orders, production, pausing, camera controls, a minimap, and a simple win condition.

## Run

```bash
npm start
```

Then open `http://localhost:3000`.

## Controls

- Left click: select a unit or hillfort
- Left drag: box-select friendly units
- Right click: move, gather, or attack
- WASD / arrow keys: pan
- Mouse wheel: zoom
- Space: pause / resume
- B: queue a spearman at the selected hillfort
- W: queue a gatherer at the selected hillfort
- R: restart
- Escape: clear selection

## Deployment

The app is intentionally dependency-free and can run as a Render Node web service. Render should use `npm start` and the `main` branch.

## Source note

The browser implementation is an adaptation of the design and rules in the supplied `first-videogame-main.zip`. It is a mock/port, not a claim that the Godot desktop project itself runs in the browser.
