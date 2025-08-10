# Jordan Nicholls — Redefined (Static Site)

This repo holds the static site for jordanicholls.com (personal brand hub).  
It deploys to Netlify directly from GitHub — **no build step required**.

## Files
- `index.html` — main landing page
- `styles.css` — site styles
- `thanks.html` — Netlify Forms success page
- `netlify.toml` — publish config (root), optional headers

## Local edits
Open `index.html` or `styles.css` in any editor, save, commit, and push.

## Web edits (no computer needed)
1. Open this repo on GitHub.
2. Click a file (e.g., `index.html`) → **Edit**.
3. Make changes → **Commit changes** (to `main`).
4. Netlify auto-deploys the update in ~30–60 seconds.

## Netlify setup (one-time)
1. Log in to Netlify → **Add new → Site → Import an existing project**.
2. Choose **GitHub** and select this repo.
3. Build command: _(leave blank)_
4. Publish directory: `/`
5. **Deploy site**.
6. Connect your custom domain under **Site settings → Domain management**.

## Rollback
Netlify keeps a deploy history. You can roll back any version from the **Deploys** tab.

## Forms
The subscribe form on `index.html` is compatible with Netlify Forms. Submissions show up in **Forms**.
