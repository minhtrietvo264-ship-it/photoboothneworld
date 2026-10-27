# tKv. x VMT Photobooth

Static photobooth for GitHub Pages.

- Camera capture and local image upload
- Frames, filters, captions and 600 × 1680 PNG export
- Photos stay in the browser and are not uploaded
- API preview uses static JSON; cloud sharing is not implemented

Publish from the main branch, root folder, in Settings → Pages. All links use relative paths to support GitHub project URLs.

For a local preview, use a static HTTP server. Camera needs HTTPS or localhost.

Live website: https://minhtrietvo264-ship-it.github.io/photoboothneworld/

Mock catalog: `frames.json`; health example: `health.json`. The remaining session endpoints in OpenAPI are design proposals.
