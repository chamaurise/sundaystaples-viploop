# Upload This Folder To GitHub

Upload the contents of this `github-export` folder to the root of:

`chamaurise/sundaystaples-viploop`

This export is intentionally static-only for Vercel. It should contain:

- `index.html`
- `styles.css`
- `app.js`
- `assets/`
- `vercel.json`
- `.vercelignore`
- `.gitignore`
- `package.json`
- `server.mjs`
- `README.md`

Important:

- Upload every file in this folder, including `package.json` and `server.mjs`.
- These two files are safe replacements for the older files currently in GitHub.
- The safe `package.json` has no `start` script.
- The safe `server.mjs` does not start a server.

Do not upload:

- `node_modules/`
- preview screenshots
- server logs

Vercel settings:

- Framework Preset: `Other`
- Build Command: blank, or `npm run build`
- Output Directory: blank
- Install Command: blank

After uploading, redeploy on Vercel with build cache unchecked.
