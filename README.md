# Sandbox Presents

Source for [sandboxpresents.com](https://sandboxpresents.com), the website for Sandbox Presents, an independent live music production company based in New York.

## How it works

The site is a single static page with no build step and no dependencies.

* `index.html` holds all markup, styles, and scripts
* Images, fliers, and the hero video sit alongside it at the repo root
* Fonts (Bebas Neue and DM Sans) load from Google Fonts
* Hosting is GitHub Pages, with the custom domain set in `CNAME`

## Run it locally

From the repo root:

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000 in a browser. Any static file server works just as well.

## Deploy

Pushing to `main` publishes the site through GitHub Pages. Changes usually go live within a minute or two.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The whole site |
| `hero-loop.mp4` | Background video for the hero section |
| `flier-*.jpg`, `flier-*.jpeg` | Event fliers shown in the events section |
| `photo1.jpg` to `photo9.jpg` | Gallery photos |
| `logo.png`, `favicon.png` | Brand marks |
| `CNAME` | Custom domain for GitHub Pages |

## Notes

* Keep media files reasonably small. `hero-loop.mp4` and `flier-pinball.jpeg` are the heaviest assets and are worth compressing if page load feels slow.
* Contact: henry@sandboxpresents.com
