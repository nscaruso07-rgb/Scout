# Put Scout online — from your phone, free

Goal: your app gets a real web address, installs to your home screen, works
offline, and YouTube links play reliably. ~10 minutes, all in your phone
browser. You'll upload the files in the `scout-app` folder.

## 1. Make a repository

1. In your phone browser, go to **github.com** and sign in.
2. Tap the **+** (top right) → **New repository**.
3. Name it **scout** (lowercase).
4. Set it to **Public**. (Pages needs public on the free plan.)
5. Tap **Create repository**.

## 2. Upload the app files

1. On the new repo page, tap **uploading an existing file** (in the
   "Quick setup" text), or go to **Add file → Upload files**.
2. Upload **everything inside the `scout-app` folder** — all the `.html`
   files, `manifest.webmanifest`, `sw.js`, and the three `icon-*.png` files.
   - On phone you may need to upload in a couple of batches; that's fine,
     just don't put them inside a subfolder — they must sit at the top level.
3. At the bottom, tap **Commit changes**.

Double-check: the repo's main page should list `index.html` directly (not
inside a folder). If it's inside a `scout-app` folder, open that folder,
select all, and move them up — or re-upload without the folder.

## 3. Turn on Pages

1. In the repo, tap **Settings** (you may need the **⋯** menu).
2. Tap **Pages** (left menu, or in the settings list).
3. Under **Branch**, choose **main** and **/ (root)**, then **Save**.
4. Wait ~1 minute. The page will show your live address:
   **https://YOURNAME.github.io/scout/**

## 4. Install it

1. Open **https://YOURNAME.github.io/scout/** in your phone browser.
2. **iPhone:** Share button → **Add to Home Screen**.
   **Android:** menu (⋮) → **Install app**.
3. You now have a **Scout** icon on your home screen. Open it — full screen,
   no browser bars, works offline, YouTube links play properly.

## Updating later

To change anything: open the repo, tap the file → pencil (edit) → make the
change → Commit. The live site updates in about a minute. Installed copies
refresh next time they're online.

## Notes

- Keep the repo public so Pages stays free. Nothing sensitive is in these
  files — they're just the app; your scouting data stays on your device.
- If a YouTube link ever won't play, it's almost always because the page was
  opened as a local file instead of the github.io address. Once it's hosted
  and installed, links work.
- Want a private, password-protected, or custom-domain version later? That's
  a small paid step (Netlify/Vercel/Cloudflare Pages all do it) — worth it
  only once you're sharing with clients.
