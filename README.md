# Website Portfolio

Personal portfolio site for Arron Wilcox, DevSecOps Engineer at MTSI.

It's a static site with no build step: `index.html` plus `assets/style.css`. Fonts load from Fontshare and Google Fonts.

## Preview locally

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Publish with GitHub Pages

Settings → Pages → Build and deployment → Source: **Deploy from a branch**, Branch: `main`, folder `/ (root)`.
The site will then be served at `https://arronelwilcox.github.io/Website-Portfolio/`.

## History

The original 2019 CIS 1140 version (`HTMLPro/`) remains in the git history. Check out commit `025facb` to see it.
