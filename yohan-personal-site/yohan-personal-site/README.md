# Lorenzo Yohan Leonor — Personal Site

A static one-page site (plain HTML/CSS/JS — no build step needed).

## Files
- `index.html` — page content
- `style.css` — all styling
- `script.js` — mobile nav toggle + footer year
- `assets/Leonor-Yohan-Resume.pdf` — downloadable résumé
- `assets/yohan-photo.jpg` — hero photo (optimized for web)

## Deploy to Vercel (free)

**Option A — no GitHub needed (fastest):**
1. Install the CLI once: `npm i -g vercel`
2. From inside this folder, run: `vercel`
3. Answer the prompts (set up and deploy → yes; link to existing project → no; project name → anything; directory → `./`). It will give you a live URL immediately.
4. To make that your permanent link, run `vercel --prod`.

**Option B — via GitHub (easier to update later):**
1. Create a new repo on GitHub and push this folder to it.
2. Go to vercel.com → **Add New → Project** → import that repo.
3. Framework preset: choose **Other** (it's a static site — no build command, no output directory needed).
4. Click **Deploy**. Every future push to the repo auto-redeploys.

Either way, Vercel gives you a free `yourproject.vercel.app` URL, and you can attach a custom domain later for free if you have one.

## Editing later
- Text lives directly in `index.html` inside each `<section>`.
- Colors and fonts are defined once at the top of `style.css` under `:root` — change them there and they apply everywhere.
- To swap the photo or résumé, replace the files in `assets/` and keep the same filenames (or update the paths in `index.html`).
