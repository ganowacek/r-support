# R & RStudio Support Hub

A static reference site covering the RStudio IDE and core tidyverse packages,
built from Posit's official cheatsheets:

- **RStudio IDE** — panes, source editor, projects, version control, package
  development, debugging, keyboard shortcuts
- **Importing Data** — readr, readxl, googlesheets4
- **Transforming Data** — dplyr
- **Strings** — stringr, plus a regular expressions primer
- **Factors** — forcats
- **Data Visualization** — ggplot2

## Viewing the site

Once GitHub Pages is enabled for this repo, the site is available at:

```
https://<username>.github.io/<repo>/
```

## Running locally

This is a plain static site (no build step). Serve the directory with any
static file server, for example:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Attribution

Function references and diagrams are adapted from the official
[Posit cheatsheets](https://posit.co/resources/cheatsheets/) (RStudio IDE,
Data Import, Data Transformation, Strings, Factors, Data Visualization),
© Posit Software, PBC, licensed under
[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
