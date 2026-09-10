# SupCom Final-Year Project Report - Revised 7 September 2026

This edition addresses the supervisor's presentation and organization comments using the 6 September 2026 rebuilt report as its source. The original edition is preserved separately.

## Structure

- General Introduction: overview, background and motivation, related work, contribution and report organization.
- Chapter I: State of the Art.
- Chapter II: System Model and Problem Formulation.
- Chapter III: Adaptive Barrier Filtering for Disturbance-Aware Navigation.
- Chapter IV: Results and Discussion.
- General Conclusion, with an explicit Future Work section.
- Appendix A: RL Training and Policy Selection.
- Appendix B: Accepted WF-IoT Paper.
- Bibliography.

The PDF has 67 pages: cover, 7 pages of front matter, 52 pages of introduction/chapters/conclusion, 3 appendix pages and 4 bibliography pages. It contains all 20 original figures and 47 bibliography entries. All six original tables are preserved; the existing metric-summary table now has a caption and is included in the seven-entry List of Tables.

## Compile

Upload the ZIP to Overleaf, select main.tex, and use pdfLaTeX. All figures and bibliography files are included. No external conversion or shell escape is required.

```text
pdflatex -interaction=nonstopmode -halt-on-error main.tex
bibtex main
pdflatex -interaction=nonstopmode -halt-on-error main.tex
pdflatex -interaction=nonstopmode -halt-on-error main.tex
```

See REVISION_NOTES.md for the changes and preservation checks.
