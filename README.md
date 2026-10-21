# Camp Zero · Viral Finds

**Live page: https://spakec.github.io/camp-zero-viral/**

TikTok posts about quitting Zyn / nicotine pouches, vaping, smoking, alcohol and caffeine that have 50K+ views and were posted in the last ~3 months. Both videos and slideshows are included. The list is collected automatically and the page refreshes itself.

- `main` branch: the page (`index.html`).
- `data` branch: `feed.json` plus a cover image for each post. A bot rewrites this branch whenever it finds something new, so don't edit it by hand.
- `apify/` on `main`: one-off Apify snapshots for the **APIFY finds** (`#apify`) and **Quit-app videos** (`#apps`) tabs, static and untouched by the bot:
  - `quitting-zyn-2026.json` — every 2026 TikTok result for "quitting zyn", with outlier scores against each creator's last 30 posts and hooks/transcripts for the top outliers.
  - `quit-apps-2026.json` — 2026 posts (10K+ views) promoting quitting apps, from app-intent searches plus the recent posts of 50+ app/UGC accounts, with outlier scores, hooks and "concepts worth copying".
  - `covers/` — thumbnails for both.
