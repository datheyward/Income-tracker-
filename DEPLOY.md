# Updating Your Income Tracker

Your app is connected to GitHub, and Vercel auto-deploys whenever you update files there.

## To push an update
1. Go to your `income-tracker-app` repo on **github.com**
2. Tap the file you want to change (usually `index.html`)
3. Tap the **pencil/edit** icon
4. Replace the content as instructed
5. Scroll down, tap **Commit changes**
6. Vercel redeploys automatically within a minute or two — no need to touch Vercel at all

## Important — read this
Your data (bills, payouts) saves to **your phone's browser storage only**. That means:
- If you clear Safari's website data or switch phones, your entries won't carry over
- It won't sync between your phone and a laptop

If you ever want it to sync across devices, that requires adding a small free database (like Supabase) — just ask and it can be wired in.

## Note on updates
This version has no offline/service-worker caching, so every time you reopen the app it loads
the latest version directly — no manual cache-clearing needed anymore.

