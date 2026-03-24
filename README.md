# 2026 Clásico Series — BW vs T3

A single-file HTML webpage for the annual BW vs T3 golf competition. No frameworks, no build tools — drop `index.html` into a GitHub repo, enable Pages, and share the link.

---

## Features

**Four tabs:**

| Tab | Contents |
|---|---|
| 📅 Itinerary | Day-by-day schedule · Hotel & Google Maps link · Weather forecast · Flight info sheet |
| 🏆 Format | Round formats, pairings, and points breakdown |
| 📊 Scorecard | Per-match result tracker with localStorage persistence |
| 📜 History | Past results with courses played and Golf Digest rankings |

**Scorecard**
- Toggle BW / ½ / T3 per match — points calculate automatically
- Scores persist across page refreshes via localStorage
- Running totals and live standings display

**Editable player names**
- Click any name in the roster to edit inline
- All matchup tables update automatically across every round

**Mobile friendly**
- Responsive layout down to 320px
- Native share sheet on mobile via the ⬆ Share button

**History tab**
- Results from 2023–2026 with host city and courses played
- Golf Digest Top 100 Public rankings linked for each course
- All-time series record

---

## Competition Format — 12 pts total

| Round | Format | Max pts |
|---|---|---|
| 1 | Shamble (2v2 match play) | 2 |
| 2 | Four-Ball / Better Ball (2v2 match play) | 2 |
| 3 | Singles (1v1 match play) | 4 |
| 4 | Team Scramble (4v4 stroke play) | 4 |

**Teams:** BW (Matthew, Eric, Michael, Dinuka) vs T3 (Sam, Spencer, Gautam, Travis)

---

## 2026 Trip — French Lick, Indiana

**Hotel:** French Lick Springs Hotel · 8670 W State Rd 56, French Lick, IN 47432

| Date | Day | Courses |
|---|---|---|
| April 30 | Arrival · Valley Links warm-up | Valley Links (9-hole ×2) |
| May 1 | Donald Ross Day — Rounds 1 & 2 | Donald Ross Course (#8 IN — Golf Digest) |
| May 2 | Pete Dye Day — Rounds 3 & 4 | Pete Dye Course (#17 — Golf Digest Top 100 Public) |
| May 3 | Departure | Optional additional golf |

---

## Deploying to GitHub Pages

### Upload files
1. Create a new public GitHub repo
2. Upload `index.html` (must be named exactly `index.html` at repo root)
3. Go to **Settings → Pages → Source: Deploy from branch → main / (root) → Save**
4. Your site is live at `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`

### Update an existing deployment
```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO
cp /path/to/new/index.html .
git add index.html
git commit -m "update"
git push
```
GitHub Pages rebuilds automatically within ~60 seconds.

### Common issues

| Problem | Fix |
|---|---|
| 404 error | Check the file is named exactly `index.html` at repo root |
| Only README shows | `index.html` is missing — upload it |
| Old version showing | Hard refresh: Cmd+Shift+R (Mac) or Ctrl+Shift+R (Windows) |
| Pages not working | Repo must be **public** on free GitHub accounts |
