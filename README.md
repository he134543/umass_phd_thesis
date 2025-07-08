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
