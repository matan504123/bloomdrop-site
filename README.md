# bloomdrop-site

The public marketing website for **BloomDrop**, a watercolor merge puzzler for iOS.

This is the GitHub Pages site for the repository **`matan504123/bloomdrop-site`**.
It is a self-contained static site — no build step, no JavaScript frameworks, and no
external fonts or CDNs. The only raster assets are the app icon / favicons shipped in the
repo (`icon-512.png`, `icon-180.png`, `favicon-32.png`, `favicon-16.png`); all decorative
illustration (paper texture, side paint-drips, feature glyphs) is inline SVG/CSS. A tiny
inline vanilla-JS snippet drives scroll-reveals and the sticky-header state.

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
sky, periwinkle, plum), a layered cold-press paper grain (inline-SVG `feTurbulence`), rounded
cards with hover states, and soft shadows. Decorative paint-drips run down the left and right
page margins. The hero pairs the real app icon with an animated watercolor splash. Motion
(hero breathe, splash-in, drip growth, scroll reveals) is tasteful and fully disabled under
`prefers-reduced-motion`. Uses the system serif/sans font stacks only.

## Publishing

Serve the repository root via GitHub Pages (branch or `/` root). The `.nojekyll` file and
root-relative paths mean it works as-is with no configuration.

## Contact

Matan Keret · matan504@gmail.com
