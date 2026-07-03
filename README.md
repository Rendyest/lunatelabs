# Lunate Labs — Brenda Luo

One-page site, no build step required. Just `index.html`.

## Deploy to GitHub Pages (5 minutes)

1. Go to https://github.com/new
   - Owner: `rendyest`
   - Repository name: `lunatelabs`
   - Public
   - Do **not** initialize with a README (you already have this one)

2. Upload the file:
   - On the new repo page, click **"uploading an existing file"**
   - Drag in `index.html` (and this `README.md` if you want)
   - Commit directly to the `main` branch

3. Turn on Pages:
   - Go to **Settings → Pages** (left sidebar, under "Code and automation")
   - Under **Build and deployment → Source**, choose **Deploy from a branch**
   - Branch: `main`, folder: `/ (root)` → **Save**

4. Wait ~1–2 minutes, then refresh the Pages settings tab. Your live URL will be:

   **https://rendyest.github.io/lunatelabs/**

That's the link to paste into the Future Caribbean Buildathon "personal website" field.

## Making edits later

- Any text change: edit `index.html` directly in the GitHub web UI (pencil icon) and commit — Pages redeploys automatically in ~1 minute.
- Headshot: currently there's no photo placeholder in the hero (the pose-tracking graphic stands in for one). If you want to add a headshot, say so and it can be dropped into the hero's right column.
- Colors, copy, and section order all live in one file, so nothing else needs to change if you tweak content.

## Command-line alternative (if you'd rather use git)

```bash
git clone https://github.com/rendyest/lunatelabs.git
cd lunatelabs
# copy index.html into this folder
git add index.html
git commit -m "Add site"
git push origin main
```

Then turn on Pages the same way as step 3 above.
