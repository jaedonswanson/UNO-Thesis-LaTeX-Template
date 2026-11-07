# UNO Thesis LaTeX Template
A reusable LaTeX starter for UNO theses. Confirm requirements with your department, school, and supervisory committee. Citation style is department-dependent; numeric citations are the editable default here.

## Start a Thesis
1. Edit the fields in `formatting/metadata.tex`.
2. Delete and replace the sample entry in `references.bib` with the path to your references made in Zotero with the [better bibtex plugin](https://github.com/retorquere/zotero-better-bibtex).
3. Add figures as needed to `Graphics/Figures/` and tables to `Graphics/Tables/`.

## Zotero and Citations
Zotero with the Better BibTeX extension makes managing refrences way easier. Export the collection in the **Better BibLaTeX** format to `references.bib`.

Cite entries in chapter text with `\parencite{citation-key}` or `\textcite{citation-key}`. `formatting/packages.tex` selects `style=numeric`; change that option only if your department requires another style. This template uses `biblatex` with Biber, not classic BibTeX.
