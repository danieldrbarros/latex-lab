# LaTeX Lab

A minimal LaTeX project that compiles with only built‑in commands — no external packages — to test LaTeX workflows on GitHub Pages.

This repository contains:

- **`main.tex`** – a sample LaTeX document with sections, math, tables, figures, citations, and a bibliography.
- **`references.bib`** – a BibTeX bibliography file.

The goal is to demonstrate a self‑contained LaTeX project that can be compiled automatically on GitHub (like Overleaf) and the PDF served via GitHub Pages.

## Compiling locally

If you have a TeX distribution installed (e.g., TeX Live, MiKTeX), you can compile the document manually:

```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex