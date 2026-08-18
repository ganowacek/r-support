# R & RStudio Support Hub

A [Quarto](https://quarto.org) website covering the RStudio IDE and core
tidyverse packages, built from Posit's official cheatsheets:

- **RStudio IDE** — panes, source editor, projects, version control, package
  development, debugging, keyboard shortcuts
- **Importing Data** — readr, readxl, googlesheets4
- **Transforming Data** — dplyr
- **Strings** — stringr, plus a regular expressions primer
- **Factors** — forcats
- **Data Visualization** — ggplot2

## Viewing the site

**https://ganowacek.github.io/r-support/**

## Project structure

Source content lives in the `.qmd` files at the repo root and is configured
by `_quarto.yml`. Rendered HTML is committed to `docs/`, which is what
GitHub Pages serves (Settings → Pages → source: `main` branch, `/docs`).

## Running locally

Requires the [Quarto CLI](https://quarto.org/docs/get-started/).

```bash
quarto preview
```

This live-reloads at `http://localhost:<port>` as you edit `.qmd` files. To
produce the static output committed to `docs/`:

```bash
quarto render
```

## Attribution

Function references and diagrams are adapted from the official
[Posit cheatsheets](https://posit.co/resources/cheatsheets/) (RStudio IDE,
Data Import, Data Transformation, Strings, Factors, Data Visualization),
© Posit Software, PBC, licensed under
[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
