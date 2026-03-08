# jonesor.github.io

Personal academic website of Owen R. Jones, Associate Professor at the University of Southern Denmark. Research on population dynamics, life history evolution, and phenology.

## Quarto website workflow

### Preview in RStudio

1. Open the project in RStudio. 
2. Open any `.qmd` file and click **Render** to preview that page.
3. For full-site preview, run `quarto preview` in the RStudio Terminal.

### Render locally

Run:

```bash
quarto render
```

Rendered output is written to `_site/`.

### Publish/update via GitHub

1. Push changes to `main`.
2. GitHub Actions runs `.github/workflows/publish.yml` and deploys the rendered Quarto site to GitHub Pages.
3. In repository settings, ensure Pages is configured to use **GitHub Actions** as the source.

## Customise content

Main content to update over time:

- `index.qmd` for short bio, current interests, and landing-page text
- `research.qmd` for research themes and current project areas
- `data-tools.qmd` for package/database/software updates
- `teaching.qmd` for current teaching portfolio
