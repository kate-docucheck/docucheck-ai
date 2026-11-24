# DocuCheck AI — one-page site

This folder contains a standalone static landing page for the Start-Up Chile application.
It does not depend on the Next.js app and can be published in a few minutes.

## 1. Replace the placeholders

Open `index.html` and replace:

No placeholders left. The contact email is `bachika1980@gmail.com` and the GitHub URL is
`https://github.com/kate-docucheck/docucheck-ai`. The five audio chapters are in `audio/`.

## Audio demo

The demo section already contains five chapters in `audio/1.ogg` … `audio/5.ogg`.
They are included in this folder, so the published site is self-contained.
The page includes a "Play all chapters" button that plays them in sequence.

## 2. Publish (pick one)

### Option A — Netlify Drop (fastest, ~2 minutes)
1. Go to https://app.netlify.com/drop
2. Drag the whole `landing` folder onto the page.
3. You get a URL like `https://random-name.netlify.app`.
4. Optionally rename the site under Site settings → Site details.

### Option B — GitHub Pages
1. Create a new repository, e.g. `docucheck-landing`.
2. Upload `index.html` to the root of that repository.
3. Repo → Settings → Pages → Source: `main` / `root` → Save.
4. Your URL will be `https://<username>.github.io/docucheck-landing/`.

### Option C — Vercel
1. Import the repository that contains this folder.
2. Framework preset: **Other**.
3. Root directory: `landing` (or publish the whole repo and set Output Directory to `landing`).
4. Deploy.

## 3. In the application form

Paste the public URL into the website field and select **An active website**
under "online presence elements".

Do not select it before the URL actually opens in a browser.
