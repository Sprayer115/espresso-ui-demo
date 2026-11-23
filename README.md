# Espresso UI Demo

- **Current prototype:** https://sprayer115.github.io/espresso-ui-demo/
- **Frozen v7 prototype (2026-11-23 morning):** https://sprayer115.github.io/espresso-ui-demo/v7/

The v7 snapshot was built from source commit [`79fb5cc8`](https://github.com/Sprayer115/espresso-ui-prototype/commit/79fb5cc89021f22c4d2d2aefa2979cd57822a07c), tagged `v7-2026-11-23` in the prototype repository. Its JavaScript and CSS bundles are identical to the current deployment; only the v7 HTML asset paths differ for subdirectory hosting.

Future updates to the current demo must leave `v7/` unchanged so earlier walkthrough results remain reproducible.

## Rollback

Revert the deployment commit that introduced `v7/` to remove the archive. The root prototype is not modified by this release. To restore an earlier current version, deploy that version's original commit instead of changing the frozen archive.
