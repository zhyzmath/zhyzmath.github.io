# Yizhou Zhao — academic homepage

Personal academic website: https://zhyzmath.github.io/

A responsive static page built with HTML and CSS. No JavaScript, package installation, or build step is required. Google Fonts are optional; system fonts provide fallbacks.

## Files

- `index.html`: biography, news, research interests, publications, education, and academic service.
- `academic.css`: responsive page styles.
- `favicon.svg`: browser icon.
- `assets/`: portrait and university emblems used by the page.
- `.nojekyll`: serves the static files directly on GitHub Pages.

## Preview locally

```sh
python3 -m http.server 4173 --bind 127.0.0.1
```

Open http://127.0.0.1:4173/.

## Publish updates

GitHub Pages publishes the root directory of the `main` branch. Edit the page or assets, inspect the changes, then commit and push:

```sh
git diff
git add index.html academic.css assets
git commit -m "Update academic homepage"
git push origin main
```

The `.gitignore` uses an explicit file allowlist. Add any new production assets to it before committing. Local archives, preview screenshots, browser artifacts, and unused templates are excluded from the repository.

## Asset sources

- Portrait: provided by Yizhou Zhao.
- [Georgia Tech seal](https://commons.wikimedia.org/wiki/File:Georgia_Tech_seal.svg).
- [University of Pennsylvania shield](https://branding.web-resources.upenn.edu/logos-and-branding/download-penn-logos).
- [Zhejiang University emblem](https://www.zju.edu.cn/572/main.htm).

University emblems identify educational affiliations and remain the marks of their respective institutions.
