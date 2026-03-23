# 2026 Clásico Series — BW vs T3

A single-file HTML webpage for tracking the annual BW vs T3 golf competition. No frameworks, no dependencies — just drop `index.html` into a GitHub repo and enable Pages.

---

## What's Inside

**Four tabs:**

| Tab | Contents |
|---|---|
| 📅 Itinerary | Day-by-day schedule for French Lick, IN (April 30 – May 3) |
| 🏆 Format | Round-by-round competition format with matchups and points |
| 📊 Scorecard | Live points tracker — enter scores and standings update in real time |
| 📜 History | Past results (2023–2025) with courses played and Golf Digest rankings |

**Format — 4 rounds, 12 points total:**
1. Shamble (match play, 2v2) — 2 pts
2. Four-Ball / Better Ball (match play, 2v2) — 2 pts
3. Singles (match play, 1v1) — 4 pts
4. Team Scramble (stroke play, 4v4) — 4 pts

**Teams:** BW (Matthew, Eric, Michael, Dinuka) vs T3 (Sam, Spencer, Gautam, Travis)

**Editable names** — click any player name in the roster to edit it; all matchup tables update automatically.

---

## How to Update on GitHub

### Replace the old webpage with this one

1. Go to your GitHub repo
2. Click `index.html` → click the **pencil (edit) icon** → select **"Delete file"** → commit
3. On the repo home page click **"Add file" → "Upload files"**
4. Drag in the new `index.html` and `README.md` → click **"Commit changes"**

That's it. GitHub Pages will rebuild automatically within ~60 seconds.

### Or via Git (command line)

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO
cp /path/to/new/index.html .
cp /path/to/README.md .
git add index.html README.md
git commit -m "2026 update: French Lick itinerary, editable names, history tab"
git push
```

---

## GitHub Pages Setup (first time only)

1. Repo **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: `main` / `(root)`
4. Save — your site will be live at `https://YOUR_USERNAME.github.io/YOUR_REPO`
