# Mohit Singh — Portfolio (Vercel Deploy)

This is a single, self-contained static site (`index.html`). No build step, no dependencies.

## Fastest way — Vercel dashboard (no GitHub needed)
1. Go to https://vercel.com and log in / sign up (free).
2. Click **Add New → Project**.
3. Choose **"Deploy without Git"** (drag-and-drop option on the import screen).
4. Drag this whole folder (or just `index.html`) into the upload area.
5. Click **Deploy**. Vercel gives you a live URL like `mohit-singh.vercel.app` in ~30 seconds.

## Recommended way — via GitHub (easier future updates)
1. Create a new GitHub repo, e.g. `mohit-portfolio`.
2. Upload `index.html` to the repo (GitHub web UI: **Add file → Upload files**).
3. Go to https://vercel.com/new, click **Import** next to your GitHub repo.
4. Framework preset: choose **"Other"** (it's plain HTML — no build command needed).
5. Click **Deploy**.
6. Every future push to the repo auto-redeploys.

## Custom domain (optional)
In the Vercel project → **Settings → Domains**, add your own domain and follow the DNS steps shown.

## Notes
- Everything (styles, script, your photo, and your resume PDF) is bundled inside this one `index.html` file — nothing else to upload.
- The "Download Resume" button works as a normal in-browser download once deployed on Vercel.
