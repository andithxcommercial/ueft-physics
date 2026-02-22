# UEFT‑2F Paper – Source Files

This directory contains the LaTeX source for the paper:

**“UEFT‑2F: A Two‑Field Coherence–Decoherence Cosmology from Unified Entanglement Field Theory”**

by Sebastian Werner (February 2026).

## Files

- `ueft_2f_paper_v2.tex` – Main LaTeX document
- `ueft2f_refs.bib` – Bibliography (BibTeX)
- (PDF will be added after compilation)

## Compilation

To generate the PDF, run:

```bash
pdflatex ueft_2f_paper_v2.tex
bibtex ueft_2f_paper_v2
pdflatex ueft_2f_paper_v2.tex
pdflatex ueft_2f_paper_v2.tex
```

Alternatively, use `latexmk`:

```bash
latexmk -pdf ueft_2f_paper_v2.tex
```

## Required LaTeX Packages

- `amsmath`, `amsfonts`, `amssymb`
- `graphicx`
- `hyperref`
- `natbib`
- `geometry`

All are included in standard TeX Live / MiKTeX distributions.

## Pre‑compiled PDF

A pre‑compiled PDF will be available via Zenodo (DOI) once the preprint is uploaded. The DOI link will be posted on the main website.

## License

The paper is shared under a Creative Commons Attribution 4.0 International (CC BY 4.0) license.