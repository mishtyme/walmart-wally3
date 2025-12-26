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

- The app vendors its runtime JS dependencies in `vendor/` so it works even on networks that block CDNs.
