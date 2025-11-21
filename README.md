# P. falciparum Outbreak Population Genomics Workshop

This repository contains materials for the *Population Genomics Workshop: Identification of Imported Cases*.

## Contents

- `2025_CiP_course_Pfal_outbreak.Rmd` — main R Markdown analysis file.
- `index.qmd` — Quarto version of the workshop for website rendering.
- `_quarto.yml` — Quarto project configuration for a website.
- `data/` — place VCFs and metadata files here (not committed by default).
- `_site/` — rendered Quarto website (not tracked; generated locally).

## Rendering the R Markdown to HTML

In R (e.g. RStudio):

```r
rmarkdown::render("2025_CiP_course_Pfal_outbreak.Rmd")
```

This will produce `2025_CiP_course_Pfal_outbreak.html` with all results and figures.

## Rendering the Quarto Website

Install Quarto, then from this folder run:

```bash
quarto render
```

This will create a website under `_site/`, which you can publish with GitHub Pages.
