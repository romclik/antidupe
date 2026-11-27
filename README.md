# Antidupe

Door counter for Roblox DOORS (doors 100–200). Built for iPad, works anywhere.

## Publish on GitHub Pages
1. Create a new GitHub repo (e.g. `antidupe`) and upload **everything in this folder** (keep the `assets` folder).
2. Repo → Settings → Pages → Source: "Deploy from a branch" → Branch `main`, folder `/ (root)` → Save.
3. After a minute it is live at `https://<your-username>.github.io/antidupe/`.
4. On the iPad: open the link in Safari → Share → Add to Home Screen. It then opens fullscreen with no browser bars.

## Hidden controls
- Hold the door number for ~1 second: go back one door (fixes a mis-tap).
- Hold the logo for ~1.5 seconds: start over from door 100.

## Tweaks
Chase timing and door numbers are constants at the top of the script in `index.html`
(`CHASE_SECONDS = 150`, etc). Special room names are in the `SPECIAL` object.
