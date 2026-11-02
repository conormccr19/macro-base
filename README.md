# MacroBase

Coming soon page for MacroBase — a single static `index.html`, no build step.

The page is served with **GitHub Pages** from the `main` branch root:

> https://macro-base.app/

## Editing

- `index.html` — the live landing page.
- `mega.html` — a longer, feature-rich version of the landing page (unlinked, kept for later use).

The page uses Google Fonts (Fraunces + IBM Plex Mono) and the team photos in the repo root. Everything else is inline, so there are no dependencies to install.

## Local preview

```sh
open index.html          # macOS
xdg-open index.html      # Linux
```

Or serve it:

```sh
python3 -m http.server 8000
```
