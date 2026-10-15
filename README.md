# TrueCAD-page

Product page for the TrueCAD Superhive listing. Plain HTML, no build step. Served by GitHub Pages at https://semtip.github.io/TrueCAD-page/

## Editing

- **Links, sale banner**: the `window.TRUECAD` block at the top of `index.html`. Set `SALE` (and optionally `SALE_CODE`) to show the banner, `''` to hide it.
- **Branding**: `theme.css` only. Colors, fonts and radii are tokens there. Add `data-theme="light"` to `<html>` to try the light preset.
- **Media**: `assets/`. The hero image and the three clip slots each have a commented `<video>` line ready to swap in.
- **Quotes**: a commented section in `index.html`. Fill it with real quotes only.

## Preview

```
python3 -m http.server
```

Open `localhost:8000/preview.html` to see the page inside a mock listing, or `index.html` on its own.

## Rules

No em dashes. Never name the underlying CAD engine or solver.
