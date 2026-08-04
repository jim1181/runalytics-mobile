# Runalytics Mobile

Static mobile helpers for Runalytics.

This repo contains only public app shells. It does **not** contain activity
data, GPS tracks, tile history, field notes, or CSV exports.

## Apps

- `index.html` / `mobile_tile_checker.html` — simple current-tile lookup.
- `tile-hunter/` — standalone Tile Hunter PWA prototype with Fog,
  Cartographer, Quests, and Realm views.

## Use the tile checker

1. Open the GitHub Pages site on your phone.
2. Choose your private `mobile_tile_lookup_250m.csv` from Files/iCloud.
3. Tap **Load selected CSV**.
4. Tap **Use my current location**.

The tile lookup CSV stays on your device/iCloud and is selected manually by the
browser.

## Use Tile Hunter

Open:

```text
https://jim1181.github.io/runalytics-mobile/tile-hunter/
```

Then load your private `mobile_tile_lookup_250m.csv` from Files/iCloud.

Tile Hunter stores its local tile database, field notes, and lightweight game
state in the browser. Use the app shell publicly; keep the CSV private.
