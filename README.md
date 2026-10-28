# PyPass Manager — Official Website

The landing page for **[PyPass Manager](https://github.com/AmiNilay/PyPass-Manager)**, a free, offline password manager for Windows.

**Live site:** https://aminilay.github.io/PyPass-official/

## What's on the page
- Hero section with the real app dashboard and Windows download buttons
- Spotlights on the v2.0 security features: **breach check** (Have I Been Pwned, k-anonymity), **phishing lookalike guard** and **Shamir emergency access**
- Overview of all features, how the encryption works, a screenshot gallery, download steps and an FAQ

## Design
- Matches the app's graphite design system (dark by default, one blue accent), using Inter and JetBrains Mono
- Light and dark themes: follows the OS setting, and the manual toggle is remembered
- Responsive from phones to wide screens, respects reduced-motion settings, and uses inline SVG icons (no icon-font download)
- A single static `index.html` with no build step, served by GitHub Pages

## Structure
```
index.html                  page markup, styles and scripts
assets/icon.png             app icon / favicon
assets/screenshots/*.png    screenshots of the app
```

## Updating
- **Download buttons** link to `releases/latest` of the app repo, so a new release appears on the site automatically.
- **Screenshots** are copied from `docs/screenshots/` in the app repo.

## Author
**Nilay Naha** · [@AmiNilay](https://github.com/AmiNilay) · niloynaha2003@gmail.com
