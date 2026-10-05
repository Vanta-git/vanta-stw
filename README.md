# Vanta SVG build

`index.svg` is the main entry point. It wraps the original Vanta HTML application
inside an SVG `<foreignObject>` and recreates its scripts so the site remains an
interactive HTML/JS application rather than a flattened image.

The original `index.html` is preserved as `index.html.backup`.

All existing Vanta assets/folders are preserved:
- `vanta/`
- `67/`
- `black/`
- `g/`

Deploy the whole folder, not just `index.svg`, because the application references
the existing JavaScript, WASM, service worker, and other assets.
