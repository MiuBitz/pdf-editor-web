# Simple PDF Editor

Small browser PDF editor for filling forms visually.

## Features
- Open PDF locally
- Add text
- Add ✓ checkmarks
- Add typed signatures
- Add PNG/JPG signatures/images
- Drag and resize overlays
- Multi-page navigation
- Export edited PDF

## Run
Because PDF.js uses JavaScript modules, run the folder through a tiny local web server instead of double-clicking `index.html`.

### Python
```bash
python -m http.server 8000
```
Then open `http://localhost:8000`.

No PDF is uploaded to a server by this project. PDF processing happens in the browser. CDN copies of PDF.js and pdf-lib are loaded from the internet.
