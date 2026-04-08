# jonesor.github.io

Personal academic website of Owen R. Jones, Associate Professor at the University of Southern Denmark. Research on population dynamics, life history evolution, and phenology.

## Quarto website workflow

### Preview in RStudio

1. Open the project in RStudio.
2. Open any `.qmd` file and click **Render** to preview that page.
3. For full-site preview, run `quarto preview` in the RStudio Terminal.

### Render locally

This site includes pages with R code chunks, so local rendering requires both Quarto and a working R installation.

Run:

```bash
quarto render
```

Rendered output is written to `_site/`.

### Publish/update via GitHub

1. Push changes to `main`.
2. GitHub Actions runs [.github/workflows/publish.yml](/Users/jones/GitHubRepos/jonesor.github.io/.github/workflows/publish.yml), installs R plus required R packages, renders the site, and deploys it to GitHub Pages.
3. In repository settings, ensure Pages is configured to use **GitHub Actions** as the source.

## Customise content

Main content to update over time:

- `index.qmd` for short bio, current interests, and landing-page text
- `research.qmd` for research themes and current project areas
- `data-tools.qmd` for package/database/software updates
- `students-collaboration.qmd` for supervision, postdoc, and collaboration information
- `teaching.qmd` for current teaching portfolio
- `contact.qmd` for affiliation and contact details
- `nest-box-project.qmd` for the standalone nest box project page, photos, and summary outputs
