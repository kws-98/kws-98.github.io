# Academic portfolio — Kamil Sikora

A starter academic website built with [Quarto](https://quarto.org/) and published through GitHub Pages.

## Before publishing

1. Review all text, particularly research status and education.
2. Replace placeholders on `cv.qmd` and add only verified publications to `publications.qmd`.
3. Optionally add `assets/academic-cv.pdf` and link to it from `cv.qmd`.
4. Edit the title and descriptions in `_quarto.yml` if desired.

## Publish to GitHub Pages

1. Create a **public** GitHub repository named `kws-98.github.io`. If you prefer a project repository, it will instead publish under a subpath.
2. Upload **the contents** of this folder to the repository's `main` branch (including the hidden `.github` directory).
3. In the repository open **Settings → Pages → Build and deployment → Source** and select **GitHub Actions**.
4. In **Actions**, check that the `Publish Quarto website` workflow succeeds. You can also run it manually using **Run workflow**.
5. Open `https://kws-98.github.io/` after deployment completes.

## Local preview (optional)

Install Quarto from https://quarto.org/docs/get-started/ then run:

```bash
quarto preview
```

For a static build:

```bash
quarto render
```

## Editing

- Each `.qmd` file is a page written in Markdown.
- The menu is configured in `_quarto.yml`.
- Colours, fonts, and cards are configured in `styles/custom.scss`.
- The website is static: it does not require Python or a backend to serve pages.

## Notes

The text is a starting draft. The website reflects doctoral status from October 2026, as supplied by the site owner. Publications, email, ORCID, and CV PDF still need verification or completion.

## Research Notes

Edit `notes.qmd` to publish short methodological notes. Draft topics are explicitly labelled as planned.

## Your website

Repository: `kws-98/kws-98.github.io` · URL: `https://kws-98.github.io/`
