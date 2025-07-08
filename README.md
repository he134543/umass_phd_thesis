# umass_phd_thesis

An unofficial LaTeX thesis template for doctoral students at the University of Massachusetts Amherst.

> ⚠️ This template is **unofficial** and not endorsed by the UMass Graduate School. Please verify formatting requirements with the most recent [UMass Thesis & Dissertation Guidelines](https://www.umass.edu/graduate/documents/guidelines-masters-theses-and-doctoral-dissertations).

## Features

- Based on the `report` class with custom formatting to meet typical UMass thesis requirements
- Pre-configured for:
  - Chapter-wise organization
  - BibTeX bibliography management
- Clean, minimal structure to help you focus on writing
- Designed for use with [Overleaf](https://www.overleaf.com), but also works with local LaTeX distributions (e.g., TeX Live, MiKTeX)

## Structure

umass_phd_thesis/
├── thesis.tex              # Main document to compile
├── references.bib          # BibTeX file for references
├── chapters/               # Individual chapter files
│   ├── chapter1.tex
│   └── ...
├── figs/                   # Figure files (e.g., PNG, PDF)
│   └── chapter1/
├── appendix/               # Optional appendix content
└── umthesis.cls            # Customized LaTeX class file

## Recommended Workflow

1. **Use Overleaf**:  
   Upload the entire project folder to Overleaf for easy writing, compiling, and collaboration.

2. **Organize Content**:  
   - Write each chapter in a separate `.tex` file under the `chapters/` directory.
   - Place all figures inside the `figs/` folder (organized by chapter is recommended).
   - Store your BibTeX entries in `references.bib`.

3. **Citations**:  
   Use `\cite{}` or `\citeA{}` to cite references from your BibTeX file.

4. **Cross-Referencing**:  
   Use the `cleveref` package for referencing figures, tables, and sections:
   ```latex
   \cref{fig:example}  % Outputs: "Figure 1"

## Notes

- The template uses double-spacing and 12pt font by default.

- Page margins are set to meet UMass requirements (1.5" left, 1" others).

- Make sure to review the final compiled PDF for formatting issues before submission.

## License

This project is released under the MIT License. You are free to modify and use it for your dissertation.
