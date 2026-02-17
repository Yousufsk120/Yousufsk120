# Memristor India Webpage

This repository contains a static landing page for **Memristor India**.

## What error was there?

The primary issue was **project mismatch**:
- `README.md` previously contained an unrelated full HTML page for **Murshidabad Organic Farm**.
- The actual project in this repository is the **Memristor India** webpage in `index.html`.

So the error was not an HTML syntax crash in `index.html`; it was incorrect project documentation/content in `README.md`.

## Files

- `index.html` — landing page with sections for About, Research, Products, Team, and Contact.

## Run locally

Open the page directly in a browser:

```bash
xdg-open index.html
```

Or serve it with Python:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.
