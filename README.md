# Slides for Data Carpentry workshop, 30 Sep - 1 Oct @ TU Delft

Here you will find the source code and rendered slides for the
[Data Carpentry with R for Social Sciences and Humanities workshop](https://4turesearchdata-carpentries.github.io/2024-09-30-ldev-delft/)
on Sep 30 and Oct 1 2024, hosted by the TU Delft.

- Introduction to R ([slides](https://alwil.github.io/data-carpentry-slides/01_intro-r.html), [source file download](/01_intro-r.qmd))
- Getting Started with Quarto ([slides](https://alwil.github.io/data-carpentry-slides/05_quarto.html), [source file download](/05_quarto.qmd))

## Usage

Download the repository

```sh
git clone -b 2409-DC-LDEV git@github.com:alwil/data-carpentry-slides.git
```


1. Create a new (orphan?) branch (e.g. 2409-DC-LDEV)
2. Modify the slide *.qmd* files, and remove those not needed
3. Commit with a tag and create a new release from the branch

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
