# Wildkind: Kiko's Pond

A pond-building science game for kids who are just learning to read. Players dig a pond, build its pump and filters, add plants and pond friends, and care for Kiko the koi.

## Run it

No build step. Serve the folder with any static server and open `index.html`:

```
npx serve .
# or
python3 -m http.server
```

Opening files straight from disk (`file://`) won't work, because pages load each other over HTTP.

## Publish on GitHub Pages

1. Push this folder to a repo.
2. Settings → Pages → Deploy from branch → `main`, folder `/ (root)`.
3. The game is served at `https://<user>.github.io/<repo>/`.

`.nojekyll` is included so Pages serves the `_ds` folder.

## Pages

| File | What it is |
| --- | --- |
| `index.html` | Redirects to the app entrance |
| `App v2.dc.html` | App entrance |
| `Garden Map v2.dc.html` | Garden map, links to each realm |
| `Ecosystem Builder.dc.html` | The koi pond game (main game) |
| `Pond Four.dc.html` | Connect-four bonus game |
| `Pond Pairs.dc.html` | Solitaire bonus game |
| `Pond Match.dc.html` | Problem → cause → fix matching game |
| `Rescue Pond.dc.html` | Second pond game: fix an old pond |
| `Beaver Dam v2.dc.html`, `Mixed-Up Words v2.dc.html` | Other realms |
| `Pond Showcase.dc.html` | Portfolio showcase of the game's design mechanics |
| `*.dc.html` without `v2` | Earlier versions, kept for reference |

## Folders

- `assets/`, `uploads/`: paintings and sprites (WebP, resized for the web)
- `_ds/`: Organic design system stylesheet and components
- `support.js`: runtime that renders the `.dc.html` pages
- `docs/`: screen rules for kids' screens and the art request list

## Saved progress

Progress is saved in the browser's localStorage. Use "Start over" in the game to reset.
