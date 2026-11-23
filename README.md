# Setter Outbound Tracker

A free, single-file data tracker for appointment setters. Log dials, pickups, DQs, pitches and sets every day, then see your conversion rates, so you can improve and show proof.

**New: multi-offer tracking.** Add an unlimited number of offers (clients, niches, scripts) and track each separately. Filter performance by offer, or compare them side by side to see which one converts best.

## Start using it (2 minutes)

**Option A: just open it**
1. Click **Code → Download ZIP** on this repo (or save `index.html`).
2. Double-click `index.html`. Done. It works offline.

**Option B: get your own live link (works on your phone)**
1. Click **Fork** (top right) to copy this repo to your GitHub.
2. In your fork: **Settings → Pages → Build and deployment → Deploy from a branch**, choose `main` / `(root)`, **Save**.
3. After about a minute your tracker is live at `https://<your-username>.github.io/Setter-Data-Tracker-/`. Bookmark it or use "Add to Home Screen" on your phone.

## How to use it

1. **Pick an offer** in *Log activity* (or press **+ New offer** and name it, e.g. "Solar - Acme").
2. Use **+ / −** (or type) to log Dials, Pickups, DQ, Pitches and Sets. Pick a different date to backfill.
3. Check **Performance**: choose a range (Today / 7 / 30 days / All) and **All offers** or a single offer.
4. Use **Offer comparison** to see dials, sets, pickup %, set % and dials-per-set for every offer.
5. **History** lists every entry; remove one with ✕.

| Metric | Formula |
|---|---|
| Pickup rate | pickups ÷ dials |
| DQ rate | DQs ÷ pickups |
| Pitch rate | pitches ÷ pickups |
| Set rate | sets ÷ pitches |
| Dials per set | dials ÷ sets |

## Your data

- Saved automatically in your browser (localStorage). Nothing is sent anywhere.
- It is per browser and device, so clearing site data erases it. Use **Export JSON** in the Backup section regularly, and **Import JSON** to restore or move to another device.
- **Export CSV** gives a spreadsheet of every entry per offer, handy as proof for clients or a portfolio.
- Upgrading from the older single-offer version? Your existing numbers are moved into "My first offer" automatically (same browser).

## Tech

One `index.html`, no build step, no dependencies. Light and dark mode follow your system.
