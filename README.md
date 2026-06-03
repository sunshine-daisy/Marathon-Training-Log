# Marathon Training Log 🏃‍♀️

A shared training tracker for the **2026 Indianapolis Monumental Marathon** (Saturday, Nov 7),
built for Lilian, Camila, and Isabela.

**Live site:** `https://sunshine-daisy.github.io/<your-repo-name>/`

## What it does
- The full 23-week plan — run/walk method, long runs on Saturday, rest on Sunday.
- Pick each week's gym mode (3× / 2× / No Gym); log every day; close out with a weekly reflection.
- A season heatmap and a family leaderboard for all three runners.
- Cloud sync to a Google Sheet, so each person's log follows her across devices.

## First-time setup on any device
1. Open the live link above.
2. In the **☁️ Cloud sync** panel, paste the Apps Script web-app URL (ends in `/exec`).
3. Enter the shared **family code**.
4. Tap your **name** at the top.
5. Click **⬇ Load from cloud** to pull your data, then turn on **Auto-sync**. Bookmark the page.

## Notes
- Data lives in a Google Sheet in Lilian's Google Drive (via Google Apps Script). Keep the
  web-app URL and family code private — anyone with both can read all three logs.
- Each runner's data is stored separately, keyed by `familycode|name`, so logs never collide.
