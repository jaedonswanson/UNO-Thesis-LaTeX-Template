# UNO Thesis LaTeX Template
A reusable LaTeX starter for UNO theses. Confirm requirements with your department, school, and supervisory committee. Citation style is department-dependent; numeric citations are the editable default here.

## Start a Thesis

1. Edit the fields in `formatting/metadata.tex`.
2. Replace the abstract placeholder in `Chapters/abstract.tex`. UNO's abstract limit is 350 words, including the title.
3. Write the chapters in `Chapters/`. Remove optional acknowledgements or appendices from `main.tex` when not needed.
4. Add figures to `Graphics/Figures/` and tables to `Graphics/Tables/`.
5. Replace the sample entry in `references.bib` with the path to your references.

## Zotero and Citations

Zotero with the Better BibTeX extension makes managing refrences way easier. Export the collection in the **Better BibLaTeX** format to `references.bib`.

Cite entries in chapter text with `\parencite{citation-key}` or `\textcite{citation-key}`. `formatting/packages.tex` selects `style=numeric`; change that option only if your department requires another style. This template uses `biblatex` with Biber, not classic BibTeX.