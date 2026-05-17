# BSC Fungal Genomics Lab

This repository contains the Quarto book source for **BSC 495: The Hidden World's Code — A Hands-On Fungal Genomics Lab** by Carlos C. Goller, adapted from the Myco-Ed curriculum.

## Project overview

The book is organized as a modular, course-based undergraduate research experience (CURE) in fungal biology and genomics, covering:

- Fungal sampling and isolation
- Phenotypic assays
- DNA sequencing workflows
- Sample submission
- Introductory genomic analyses

Core project configuration is in [`_quarto.yml`](./_quarto.yml), where the book structure, chapter order, and output formats are defined.

## Module slides

- [Module 0 Slides](https://ccgoller.github.io/bsc-fungal-genomics-lab/module0.html)
- [Module 1 Slides](https://ccgoller.github.io/bsc-fungal-genomics-lab/module1.html)
- [Module 2 Slides](https://ccgoller.github.io/bsc-fungal-genomics-lab/module2.html)
- [Module 3 Slides](https://ccgoller.github.io/bsc-fungal-genomics-lab/module3.html)
- [Module 4 Slides](https://ccgoller.github.io/bsc-fungal-genomics-lab/module4.html)
- [Module 5 Slides](https://ccgoller.github.io/bsc-fungal-genomics-lab/module5.html)
- [Module 6 Slides](https://ccgoller.github.io/bsc-fungal-genomics-lab/module6.html)
- [Module 7 Slides](https://ccgoller.github.io/bsc-fungal-genomics-lab/module7.html)

## Repository structure

- `index.qmd` — preface
- `intro.qmd` — introduction
- `module0.qmd` to `module7.qmd` — course modules
- `summary.qmd` — summary chapter
- `about.qmd` — author page
- `references.qmd` / `references.bib` — references
- `_quarto.yml` — Quarto book configuration
- `.github/workflows/` — GitHub Actions workflows for rendering and deployment

## Prerequisites

- [Quarto](https://quarto.org/docs/get-started/)
- (Optional, for PDF output) TinyTeX or a LaTeX distribution

## Build locally

From the repository root:

```bash
quarto render
```

Render HTML only:

```bash
quarto render --to html
```

Preview while editing:

```bash
quarto preview
```

## Publish / deployment

GitHub Actions workflows in `.github/workflows/` are configured to render and deploy the book to GitHub Pages on pushes to `main`.

## Source curriculum

- Myco-Ed curriculum: https://myco-ed.github.io/myco-ed/
- Workbook source cited in the book intro: https://dx.doi.org/10.17504/protocols.io.rm7vzqd5xvx1/v1
