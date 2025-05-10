# Analytic Study of Thermal-Rotational Coupling in Cryogenic Superconducting Toroids

This repository contains the LaTeX source code for the paper "Analytic Study of Thermal-Rotational Coupling in Cryogenic Superconducting Toroids" by Teodor Berger, published in May 2025. The study investigates thermal-rotational coupling in a cryogenically cooled superconducting torus.

## Metadata
- **Author**: Teodor Berger
- **License**: Creative Commons Attribution 4.0 International (CC BY 4.0)
- **Keywords**: Superconductivity, Thermal-Rotational Coupling, Cryogenic Toroids, Péclet Number, Magnetic Reynolds Number
- **Funding**: N/A

## Project Structure
- `main.tex`: Main LaTeX file
- `references.bib`: Bibliography file
- `chapters/`: Individual section files
- `assets/`: Figures and tables (if applicable)

## How to Compile
1. Install a LaTeX distribution (e.g., TeX Live, MiKTeX).
2. Ensure required packages (`natbib`, `amsmath`, `amssymb`, `geometry`, `hyperref`, `setspace`) are installed.
3. Compile `main.tex` using:
   ```bash
   pdflatex main.tex
   bibtex main
   pdflatex main.tex
   pdflatex main.tex
