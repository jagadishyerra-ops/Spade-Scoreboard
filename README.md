# Spade Scoreboard

Static scoreboard for the spade card game. Deployed on Vercel.

## One-time setup

1. Create a new empty repo on GitHub (e.g. `spade-scoreboard`) — don't
   add a README/license there, since you already have files locally.

2. In this folder, run:
   ```
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/<your-username>/spade-scoreboard.git
   git push -u origin main
   ```

3. Go to vercel.com → **Add New → Project → Import Git Repository**,
   pick this repo, and click **Deploy**. No config needed — it's a
   plain static site.

4. You'll get a permanent URL like `spade-scoreboard.vercel.app`.
   Share that with the group.

## Updating after this

Whenever you get an updated `index.html` (or a new `og-image.png`)
from Claude:

1. Replace the file(s) in this folder.
2. Run:
   ```
   git add .
   git commit -m "update scoreboard"
   git push
   ```
3. Vercel auto-deploys within a few seconds. Same URL, new version —
   no need to touch the Vercel dashboard again.
