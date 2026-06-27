# Marathon Training Log 🏃‍♀️🥇

A shared run/walk training tracker for the **2026 CNO Financial Indianapolis Monumental Marathon**
(Saturday, **November 7, 2026**, 8:00 a.m.), built for **Lilian, Isabela, and Camila**.

**Live site:** `https://sunshine-daisy.github.io/<your-repo-name>/`

---

## The plan
- **19 weeks**, starting **Monday, June 29, 2026**, ending on race day.
- **Run days:** Mon · Wed · Sat — Saturday is the long run (Team World Vision group run).
- **Gym 💪 days:** Tue · Thu · Sun. **Friday = rest** before the long run.
- Built on the **run/walk method**, starting gentle (run 30s / walk 90s) and growing the
  running intervals week by week, then long runs that peak at **18 miles** before tapering.
- The race has a **7-hour limit (16:00 min/mile)** — so the goal is to run/walk *under* that pace.

## Logging a day
Each day card has **Mark done**, a **feeling** (😣 😐 😄), and a **notes** box.
Running days also have three quick fields:
- **mi** — total distance (run + walk)
- **min** — total time for the whole session
- **ran** — how long you actually ran (your stamina number; toggle **sec / min**)

The moment you fill in **mi + min**, a **pace badge** appears showing your min/mile and whether
you're **under the 16:00 cutoff and by how much** — your "would I have made the sweeper?" check.
Daily miles auto-add into each week's total.

## Finding your way around
- **Big date** at the top of each week, plus **prev / next**, a **jump-to-today** button,
  and a week dropdown.
- **↺ Reset week** sits right in the week bar; each day card has its own **↺** to clear just that day.
- **Season heatmap** shows all 19 weeks at a glance.
- **🏅 Family leaderboard** compares Lilian, Isabela, and Camila (toggle in the profile bar).
- **Gold note banners** surface at the right time: race switch-deadline reminder (Wk 1),
  interval-flexibility tip (Wk 2), the **Magic Mile** test (Wk 3), and the
  **full-vs-half decision** checkpoints (Wks 14–16).

## First-time setup on any device
1. Open the live link above.
2. In the **☁️ Cloud sync** panel, paste the Apps Script web-app URL (ends in `/exec`).
3. Enter the shared **family code**.
4. Tap your **name** at the top.
5. Click **⬇ Load from cloud**, then turn on **Auto-sync**. Bookmark the page.

(See `Marathon_Cloud_Sync_SETUP.md` for the one-time Google Sheet + Apps Script setup.)

## Updating the tracker
The site serves **`index.html`**. To push a new version:
GitHub repo → **Add file → Upload files** → drag in the new `index.html` → **Commit**,
then refresh on your phone (favicons cache hard, so give it a moment).
Your saved settings and logged data stay put.

## Notes
- Data lives in a Google Sheet in Lilian's Google Drive (via Google Apps Script).
  Keep the web-app URL and family code private — anyone with both can read all three logs.
- Each runner's data is stored separately, keyed by `familycode|name`, so logs never collide.
- Works offline / on the downloaded file; cloud sync just keeps devices in step.
