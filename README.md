# Showcases.dev

A lightweight, static coming-soon page for `showcases.dev`. It has no build
step, package dependencies, or external assets.

## Preview locally

From this folder, run:

```powershell
python -m http.server 8000
```

Then open <http://localhost:8000>.

## Deploy

Copy `index.html` into the Nginx document root configured for
`showcases.dev`. Keep this site separate from the Gorbit and GDS app roots.
