# WicketVerse — cricket gaming website

A responsive, static website prototype with eight interactive cricket/ IPL game modes. It uses plain HTML, CSS and JavaScript, so it can be deployed to Vercel without a build step.

## Run locally

Open `index.html` in a browser, or run a local static server from this folder:

```bash
python -m http.server 3000
```

Then visit http://localhost:3000.

## Deploy to Vercel

1. Create a GitHub repository and upload the contents of this folder.
2. Sign in to Vercel and choose **Add New → Project**.
3. Import the GitHub repository.
4. Keep the framework preset as **Other**. Leave build command and output directory blank (static files are served from the project root).
5. Deploy. Vercel will provide a preview URL.
6. Add a custom domain in the Vercel project settings when ready.

## Before public launch

- Replace `YOUR-DOMAIN.example` in `robots.txt` and `sitemap.xml` with the real domain.
- Add a privacy policy and contact/about pages before enabling analytics or accounts.
- Verify cricket statistics, historical IPL facts, player data and all answer sets against trusted sources.
- Add original or properly licensed imagery and check trademark/league branding before using official logos.
- Connect a backend (e.g. Supabase) for real accounts, cross-device streaks, saved teams and global leaderboards. Current progress is stored only in the visitor's browser where applicable.

## Current prototype limitations

- Daily puzzle rotation is date-based and uses a small sample pool.
- IPL Stat Detective and some game modes use deliberately simplified clue data, not a live stats feed.
- Cricket Connections is a sample puzzle, Build Your XI has a limited sample player pool, and Auction Simulator uses fictional demo prices.
- No real-time match scores, live IPL schedule, user accounts, global leaderboard or server-side anti-cheat are connected yet.
