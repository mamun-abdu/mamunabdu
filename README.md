# mamunabdu

The "coming soon" page served at **[mamunabdu.pro.bd](https://mamunabdu.pro.bd)**.

It's a single `index.html` with a retro pixel style (Press Start 2P and Silkscreen fonts) and Tailwind loaded from its CDN. There's no build step.

My main site, [mamunabdu.com](https://mamunabdu.com), lives in a separate repo: [mamun-abdu/mamunabdu.com](https://github.com/mamun-abdu/mamunabdu.com).

## Run it locally

Open `index.html` in a browser, or serve the folder:

```bash
git clone https://github.com/mamun-abdu/mamunabdu.git
cd mamunabdu
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Files

- `index.html`: the whole page
- `CNAME`: points GitHub Pages at `mamunabdu.pro.bd`
- `.nojekyll`: tells GitHub Pages to serve the files as they are
