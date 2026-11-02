# MacroBase

Coming soon page for MacroBase — a single static `index.html`, no build step.

The page is served with **GitHub Pages** from the `main` branch root:

> https://conormccr19.github.io/macro-base/

## Editing

- `index.html` — the live landing page.
- `mega.html` — a longer, feature-rich version of the landing page (unlinked, kept for later use).

Everything is inline (CSS, SVG, JS), so there are no fonts or assets to load and no dependencies to install.

## Local preview

```sh
open index.html          # macOS
xdg-open index.html      # Linux
```

Or serve it:

```sh
python3 -m http.server 8000
```
