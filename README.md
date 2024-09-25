# Slides for Data Carpentry workshop, June 20-21 @ VU

Here you will find the source code and rendered slides for the
[Data Carpentry with R for Social Sciences and Humanities workshop](https://ubvu.github.io/2024-06-20-ldev-amsterdam/)
on 20-21 June, hosted by the VU.

- Starting with Data ([slides](https://alwil.github.io/data-carpentry-slides/02_start-data.html), [source file download](/02_start-data.qmd))
- Data Visualisation with ggplot2 ([slides](https://alwil.github.io/data-carpentry-slides/04_data-viz.html), [source file download](/04_data-viz.qmd))
- Getting Started with Quarto ([slides](https://alwil.github.io/data-carpentry-slides/05_quarto.html), [source file download](/05_quarto.qmd))

## Usage

Download the repository

```sh
git clone -b 2406-DC-LDEV git@github.com:bbartholdy/data-carpentry-slides.git
```

Restore packages

```r
renv::init()
```

Render slides

```sh
quarto render <slides file>.qmd
```
or use the Render button in RStudio.

## Licenses

Code for slides is licensed under [The Unlicense](LICENSE)

Images by Allison Horst are licensed under [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/legalcode.en).
