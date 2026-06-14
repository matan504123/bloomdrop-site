# bloomdrop-site

The public marketing website for **BloomDrop**, a watercolor merge puzzler for iOS.

This is the GitHub Pages site for the repository **`matan504123/bloomdrop-site`**.
It is a self-contained static site — no build step, no JavaScript frameworks, no
external fonts or CDNs, and no external image assets (all illustration is inline SVG).

## Structure

| File | Live URL | Purpose |
|------|----------|---------|
| `index.html` | `/` | Marketing landing page (hero, features, how-to-play, privacy band) |
| `privacy/index.html` | `/privacy/` | Privacy policy |
| `support/index.html` | `/support/` | Support / FAQ |
| `style.css` | `/style.css` | Shared stylesheet (linked root-relative so it works from subpaths) |
| `.nojekyll` | — | Tells GitHub Pages to serve all paths plainly (no Jekyll processing) |

## Design

Watercolor / cold-press paper aesthetic: a warm cream paper background with soft layered
radial-gradient color "blooms" in the game's seven-tier palette (rose, peach, butter, sage,
sky, periwinkle, plum), a subtle CSS paper grain, rounded cards, and soft shadows. The hero
illustration and logo are pure inline SVG. Uses the system serif font stack only.

## Publishing

Serve the repository root via GitHub Pages (branch or `/` root). The `.nojekyll` file and
root-relative paths mean it works as-is with no configuration.

## Contact

Matan Keret · matan504@gmail.com
