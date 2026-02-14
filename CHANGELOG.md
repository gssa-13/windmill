## [2.0.0] (2026-02-14)

### Major Upgrades
- **Tailwind CSS v4.1.18**: Complete migration from v1.4.6. Updated to "CSS-first" configuration (`tailwind.config.js` removed).
- **Alpine.js v3.15.8**: Upgrade from v2.x. Modernized syntax (`x-show.transition` → `x-transition`) and resolved reactivity conflicts.
- **Chart.js v4.5.1**: Upgrade from v2.9.3. Chart component logic refactored.

### Fixes & Improvements
- **Dark Mode Persistence**: Fixed "Flash of Unstyled Content" (FOUC) using inline script in `<head>` of all pages.
- **Stable Navigation**: Fixed bug where theme reverted when navigating between Dashboard and other pages (removed conflict between `classList.toggle` and Alpine).
- **Local Compatibility**: Removed cache-busting parameters (`?v=...`) on local assets to avoid CORS errors when running from `file://`.

### Cleanup
- Removed temporary files and obsolete build scripts.

## [1.0.2](https://github.com/estevanmaito/windmill-dashboard/compare/1.0.1...1.0.2) (2020-07-18)

This is the first real "release". Nothing has changed, except for some SEO meta tags, that are no longer needed as the project is no longer hosted isolated.

This way you don't have to delete almost half of the `index.html` head just to start a project.

## 1.0.1 (2020-07-01)
