# Changelog

## v1.1.1 - September 27, 2026

- Move `lodash`, `quill` and `raw-loader` to `devDependencies`: they are only needed to build `video-resize.min.js`, which bundles them. `quill` becomes a peer dependency (the module uses `window.Quill`)
- Publish only the bundle, README and CHANGELOG

## v1.1.0 - June 26, 2019

- Refactoring forked version
