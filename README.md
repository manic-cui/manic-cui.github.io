# manic-cui.github.io

Source of Manni Cui's homepage: **https://manic-cui.github.io** (English) and **https://manic-cui.github.io/zh/** (中文).

Plain static HTML served by GitHub Pages; there is no build step.

```
index.html                         English homepage
zh/index.html                      Chinese homepage (the two pages link to each other)
projects/rethinking-the-readout/   project page: Rethinking the Readout (NeurIPS 2026)
projects/cure/                     project page: CuRe
assets/css/style.css               homepage styles
assets/img/                        paper teasers and favicon
assets/cv/Manni_Cui_CV.pdf         CV (opened by the "CV" button)
assets/fonts/                      self-hosted fonts (Newsreader, IBM Plex Sans; SIL OFL)
```

Fonts are self-hosted so the pages load the same everywhere, including mainland China.

## Editing

- The English and Chinese pages are separate files; when you change one, change the other too.
- To update the CV, replace `assets/cv/Manni_Cui_CV.pdf`.
- To preview locally, open `index.html` in a browser, or run `python3 -m http.server 8000` and visit http://localhost:8000.
