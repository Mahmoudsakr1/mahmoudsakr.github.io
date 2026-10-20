# Mahmoud Sakr: portfolio website

A static site with no build step. `index.html`, `cv.pdf` and the `images/` folder are the whole site.

## Put it online (free, about 5 minutes)

**Netlify Drop (easiest)**
1. Go to https://app.netlify.com/drop
2. Drag this `website` folder onto the page.
3. You get a live link. Under *Site settings → Change site name*, rename it, e.g. `mahmoudsakr.netlify.app`.

**GitHub Pages**
1. Create a public repo named `mahmoudsakr.github.io`.
2. Upload everything in this folder.
3. Your site goes live at `https://mahmoudsakr.github.io` (check *Settings → Pages*).

**Custom domain (optional):** buy `mahmoudsakr.com` or similar, then point it at Netlify or GitHub Pages from that service's domain settings.

## Editing

- Text lives in `index.html`. Experience entries, gallery photos and the leadership game cards are arrays near the bottom, inside the `<script>` block.
- To add photos, drop a `.jpg` into `images/` (around 1400px on the long side) and add a line to the `photos` list.
- The page follows the visitor's light or dark mode automatically.
