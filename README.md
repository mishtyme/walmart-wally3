# walmart-wally3

Single-page site for **Wally AMP** (Autonomous Merchant Partner).

## Run locally

This project is intentionally dependency-light and can be opened directly as a static file.

- Open `index.html` in a browser, or
- Serve the folder:

```bash
cd /workspace
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Notes

- The site is **plain HTML/CSS/JS** (no React/Babel/Tailwind runtime), to ensure it loads reliably on desktop and mobile.
