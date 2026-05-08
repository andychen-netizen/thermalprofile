# Composites Manufacturing

A Joby-inspired landing page for a composites manufacturing company. The hero CTA button is, regrettably, unclickable.

## Hosting on GitHub Pages

1. **Create a new public repository on GitHub.** Name it whatever you want — e.g. `composites-site`.
2. **Upload `index.html`** to the root of the repo (drag it into the GitHub web UI, or use git from the command line).
3. **Enable GitHub Pages.** In the repo, go to **Settings → Pages**. Under "Build and deployment":
   - **Source:** Deploy from a branch
   - **Branch:** `main` (or `master`), folder `/ (root)`
   - Click **Save**.
4. **Wait ~1 minute.** GitHub will give you a URL like:
   ```
   https://<your-username>.github.io/<repo-name>/
   ```

That's it. The page will be live.

## Image sources

All images are loaded via direct hotlink — no files to upload. They'll work as-is from any browser viewing the live site.

- **Hero (S4 aircraft):** US Air Force photo of the Joby S4 at Edwards AFB, public domain, hosted on Wikimedia Commons.
- **Carbon fiber section, capability tiles:** Free-license photos from Unsplash.

If any image stops loading down the road (rare, but possible), you can swap the `src` URLs in `index.html` for any other image URL.

### Want images bundled locally instead?

Download each image, drop them in an `images/` folder next to `index.html`, and replace the `src` URLs with relative paths like `images/s4.jpg`. Recommended if you want the site to be fully self-contained.

## Editing

Edit `index.html` directly in the GitHub web UI (pencil icon) or push changes via git. Pages will rebuild automatically within a minute.
