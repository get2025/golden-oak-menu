# The Golden Oak – QR Dining Experience (prototype)

## Folder structure
```
index.html
models/
  biryani.glb
  maggie.glb
  pasta.glb
  pizza.glb
```

## Deploy on GitHub Pages
1. Create a repo, upload `index.html` and the `models/` folder (with your 4 .glb files).
2. Settings → Pages → Source: `main` branch, `/ (root)` → Save.
3. Open `https://<username>.github.io/<repo>/`

## Per-table QR codes
Make one QR per table that points to: `https://<username>.github.io/<repo>/?table=14`
(change the number for each table).

## Edit links / WiFi
Open `index.html`, find `CONFIG` near the top of the script (Google Reviews, YouTube, Instagram, WiFi name/password).

## Staff dashboard
`https://<username>.github.io/<repo>/#/staff` (demo mode: orders are stored in the browser; a real backend is needed for live multi-device orders).
