# GAINZ — Workout Tracker PWA

A progressive web app for tracking your weekly Push/Pull/Leg workouts.

## Files
- `index.html` — the entire app (single file)
- `manifest.json` — PWA config
- `sw.js` — service worker (offline support)
- `icon-192.png` / `icon-512.png` — app icons

## Deploy to GitHub Pages (free, runs on your phone like a native app)

### Step 1: Create a GitHub repo
1. Go to https://github.com and create a new **public** repository
2. Name it `gainz` (or anything you like)

### Step 2: Push these files
```bash
git init
git add .
git commit -m "Initial GAINZ app"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/gainz.git
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. Go to your repo → **Settings** → **Pages**
2. Source: **Deploy from branch** → `main` → `/ (root)`
3. Click **Save**
4. Wait 1–2 minutes → your app is live at `https://YOUR_USERNAME.github.io/gainz`

### Step 4: Install on your phone as a native app

**iPhone (Safari):**
1. Open the URL in Safari
2. Tap the **Share** button (box with arrow)
3. Tap **"Add to Home Screen"**
4. Tap **Add** — it now appears on your home screen like a native app

**Android (Chrome):**
1. Open the URL in Chrome
2. Tap the 3-dot menu → **"Add to Home screen"**
3. Or Chrome may show an install banner automatically

## How to update the app
Edit `index.html`, commit, and push to GitHub. GitHub Pages updates automatically within minutes.

## Features
- **Tue/Thu/Sun workout program** with your exact exercises
- **GAIN mode** (8/6/6/6 reps) and **SHRED mode** (10 reps all sets)
- **Rest timers** — set timer (90s default) and exercise timer (3min default)
- **Weight tracking** per set with PR detection
- **Body weight log** with trend chart
- **Smart suggestions** on progressive overload and mode switching
- **Works offline** — all data stored locally on your phone
