# Deploy Your Income Tracker to Vercel

You don't need to know how to code for this. Follow these steps.

## 1. Unzip the file
Unzip `income-tracker-app.zip` on your computer. You'll get a folder with these files:
- index.html
- manifest.json
- sw.js
- icon-192.png
- icon-512.png
- apple-touch-icon.png

## 2. Go to Vercel
1. Go to **vercel.com** and log in (use the same account you used for your intake form site).
2. Click **Add New** → **Project**.
3. Look for a box that says **"Deploy without Git"** or a drag-and-drop area — it usually says something like *"Drop your folder here to deploy"*.
4. Drag the whole unzipped folder into that box.
5. Click **Deploy**.

Vercel will give you a live link that looks like:
`income-tracker-xxxxx.vercel.app`

## 3. Rename it (optional but nice)
In your Vercel project settings, go to **Domains** and change the auto-generated name to something like:
`dana-income-tracker.vercel.app`

## 4. Add it to your phone's home screen
**iPhone (Safari):**
1. Open your new link in Safari.
2. Tap the **Share** icon (square with an arrow).
3. Tap **Add to Home Screen**.
4. Tap **Add**.

**Android (Chrome):**
1. Open your new link in Chrome.
2. Tap the **⋮** menu.
3. Tap **Add to Home screen** (or you may see an automatic "Install app" prompt).

Now it opens full-screen with its own icon, just like a real app.

## Important — read this
Your data (bills, payouts) saves to **that one phone/browser only**, using its local storage. That means:
- If you clear your browser data or switch phones, your entries won't carry over.
- It won't sync between your phone and a laptop.

If you ever want it to sync across devices, that requires adding a small free database (like Supabase) — just let me know and I can wire that in later.

## Updating the app later
If you want new features added, come back to this chat (or a new one) and ask. I'll hand you an updated folder — just repeat steps 1–2 to redeploy over the same Vercel project.
