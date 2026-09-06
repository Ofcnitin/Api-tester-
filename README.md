# Astra API Tester

A tiny static GitHub Pages app for testing an Experiential Labs `xpl_...` API key.

## Important security note

This app sends the API key directly from your browser. **Do not put the key into the source code, GitHub repository, or GitHub Actions secrets for this demo.** Enter it into the password field at runtime.

The key is not persisted by this page.

## GitHub Pages

1. Create a GitHub repository.
2. Upload `index.html` and `README.md`.
3. Go to **Settings → Pages**.
4. Choose **Deploy from a branch**, select `main` and `/root`.
5. Open the generated Pages URL.

If the API rejects the browser request because of CORS, the API needs a server-side proxy (for example, a Cloudflare Worker). Do not work around CORS by exposing the key publicly.
