# Revision Notes - 7 September 2026

## Response to the Comments

1. The cover's editable text is English. The supplied institutional logos are preserved, including their official lettering.
2. The cover header shows SupCom only; running headers identify SupCom. The KAUST logo is placed below "Work proposed and carried in collaboration with".
3. The full report title and subtitle use bold type consistently.
4. The acknowledgements are expanded while retaining the named supervisors and institutions.
5. The nine numbered chapters are reorganized into four, preceded by an unnumbered General Introduction. Existing background chapters become sections of State of the Art; the existing velocity model and clearance equations move to System Model and Problem Formulation. Short connecting text explains the navigation problem. The proposed method has a descriptive chapter title. The practical-extension material is a section within Results and Discussion.
6. The existing conclusion is retained, renamed General Conclusion, and given a visible Future Work section with a short expansion based on the report's existing limitations.
7. Appendix B records the accepted WF-IoT paper. Acceptance status follows the author's request. The title and author list follow the manuscript already associated with this report (output/source/main.tex and root_refs.bib); no DOI, publication date or proceedings details have been invented.
8. A List of Tables is added. The existing unnumbered metric-summary table receives a caption; its entries are unchanged.
9. Chapter and section headings use title case and parallel descriptive phrasing. The contents, figure/table numbering and internal links are regenerated.
10. The main benchmark's existing arena dimensions, occupancy, split, control rate, command bounds, clearance settings and terminal conditions now appear at the start of Chapter IV. The existing practical-extension description is summarized there with 72 static and 12/20/40 dynamic obstacles. No undocumented extension-arena dimensions are inferred from images.

## Preservation and Validation

- All 20 original figure environments, including their graphics/TikZ code and captions, match the original source exactly.
- All 30 supplied files in the figures directory have matching SHA-256 hashes.
- All 31 equation environments and the aligned-equation environment match exactly.
- All six original table environments match exactly; no result values were changed.
- Original technical paragraphs are retained, with changes limited to structural headings, cross-references and roadmap wording. The contribution overview and system-model material were relocated. The acknowledgements and requested connecting/end-matter text are the editorial additions.
- Successful final pdfLaTeX/BibTeX build; no unresolved citations/references, overfull boxes, underfull boxes or LaTeX warnings in the final log.
- Rendered pages reviewed for layout, including the cover, contents, lists, chapter transitions, all figures and tables, general conclusion and publication appendix. Sparse spill pages introduced during restructuring were corrected.
- The original report and its source package were not overwritten.
