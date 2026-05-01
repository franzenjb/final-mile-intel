# Final Mile Intelligence Map

Single-file Leaflet operational dashboard for Red Cross / GIS planning.
Live NWS hazards, infrastructure layers, AI-assisted operational briefings.

## Run locally
Double-click `index.html`. No build step, no API keys.

## Deploy
Auto-deploys to Vercel on push to `main`.

## Edit
- `index.html` is the published file (Vercel + GitHub Pages serve this).
- `final-mile-intelligence-map.html` is a duplicate kept for direct downloads.
- Keep them in sync, or drop the duplicate if you don't need it.

## LightRAG
Flip `LIGHTRAG_CONFIG.enabled = true` in the HTML to call a local LightRAG
server at `http://localhost:8020/query`.

## Demo data
Replace `DEMO_INFRASTRUCTURE` with real feature service data when ready.
