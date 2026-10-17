# RACEL Global Ventures — Premium Corporate Website Package

This folder is a static, responsive HTML/CSS/JavaScript website concept based on the latest RACEL corporate homepage mockup, with a stronger global aviation/logistics operator feel.

## Files
- `index.html` — website content and page structure
- `styles.css` — responsive visual design
- `script.js` — mobile navigation and dynamic copyright year
- `assets/` — local image assets and mockup reference
- `assets/homepage-mockup-reference.jpg` — complete visual mockup for comparison

## Preview locally
Open `index.html` in a modern browser. For local development, run a static server in this folder, e.g. `python3 -m http.server 8000`, then open `http://localhost:8000`.

## Upload to GitHub
Upload the *contents* of this folder (not the enclosing folder) into the root of `Racel-website/demo`. Keep `index.html` at the repository root. Then enable GitHub Pages in Settings → Pages → Deploy from a branch → `main` → `/(root)`.

## Important visual fidelity note
This package implements the layout, hierarchy, colors, and sections from the latest mockup as a responsive website. Browser rendering cannot be pixel-identical to a generated mockup image at every screen size. Image assets are cropped from the mockup concept itself to keep the visual direction consistent. The wordmark crop is a temporary concept crop from the mockup, **not a production-ready transparent logo**. Replace `assets/racel-wordmark-concept.jpg` with RACEL's approved high-resolution logo asset before production.

## Content / production checklist
- Confirm the official logo and brand guide, and replace the temporary wordmark crop.
- Replace mockup-cropped images with approved original photography for a production site.
- Confirm company contact details and privacy/terms pages.
- Partner logos are intentionally omitted to avoid implying unverified partnerships.
- News cards are illustrative placeholders; replace them with approved announcements.
- The impact section uses non-numeric descriptions rather than inventing actual company performance statistics.
- Contact CTA opens the published RACEL contact email; no data collection form is implemented in this static concept.

## Deployment
GitHub Pages can serve this static website. No build tools, npm packages, server runtime, or external API keys are required. Google Fonts is optional; system fallbacks are included.


## Latest visual fixes
- Replaced the temporary cropped wordmark with the supplied RACEL Global Ventures logo.
- Corrected logo sizing to preserve its natural horizontal proportions in the header and footer.
- Reduced hero heading sizing slightly on desktop and mobile to prevent clipping.

Upload the contents of this folder to the repository root, keeping the `assets/` folder and its images together. Replace existing files when prompted.


## Footer logo file (important)
The footer now references `assets/racel-wordmark-white-gold.jpg`, the dedicated white-and-gold logo for the dark navy footer. Place that exact image file inside the `assets/` folder before deployment. The original header logo reference remains `assets/racel-wordmark-concept.jpg`. The white-and-gold footer image was not bundled because it was not present among the available local files when this package was regenerated.
