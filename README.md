# GlowCube Ultimate (PWA)

Game puzzle neon by Fatur Entertainment.

## Isi folder
- `index.html` – game
- `manifest.json`, `sw.js`, `icons/` – file PWA
- `klik.mp3`, `clear.mp3`, `musik.mp3` – suara & musik game

## Cara upload ke GitHub Pages
1. Buat repository baru di GitHub (mis. `glowcube`).
2. Upload SEMUA isi folder ini (termasuk 3 file mp3 dan folder `icons`).
3. Settings → Pages → Source: `Deploy from a branch` → Branch: `main` / `(root)` → Save.
4. Buka `https://USERNAME.github.io/glowcube/` di Chrome HP → menu ⋮ → **Install app** / **Add to Home screen**.

Kalau mengubah file, naikkan `CACHE = 'glowcube-v1'` di `sw.js` (v2, v3, dst.) supaya pengguna dapat versi terbaru.
