# EDGE · Turbojet Programme — interactive briefing

A static website: `index.html`, `styles.css` and `assets/`. No build step.

## View locally
Double-click `index.html`, or serve the folder:

```bash
python3 -m http.server 8080
```

Then open http://localhost:8080. It needs an internet connection, because Three.js (the 3D engine) and the fonts load from public CDNs.

## Put it online
Upload the whole `platform/` folder to any static host (Netlify, Vercel, Azure Static Web Apps, S3, or an internal web server). The page contains commercial financials, so host it behind access control (password or SSO).

## Presenting
- `→` / `↓` / `Space` go to the next section. In the Manufacturing section they step through Phases 01–03 first.
- `←` / `↑` go back. `F` turns fullscreen on and off.
- Portfolio: switch between NJ40 and NJ120, drag to rotate the engine, use the throttle, and turn on the exploded view.
- Factory: filter zones by phase, show the material flow, and switch to the 3D perspective. Click any zone for its details.
