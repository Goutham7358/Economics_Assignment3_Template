Combined report and reviewed source
===================================

main_combined.tex now contains the complete approved shortening review as of
18 November 2026. The review was a full report, not just Sections 4 and 5.
The project-root sections4_5_shortening_review.tex preserves the review copy.

This includes the updated methods, shortened Sections 4 and 5, integrated
Section 6, agreed Section 7 recommendations and supporting appendices.
O3 uses whole-season route counts. O1 follows the supplied code.

Build from the repository root with a TeX distribution containing Biber:

  latexmk -pdf -outdir=review/shortening/build main_combined.tex

On Overleaf, select main_combined.tex as the main document.
The saved PDF is output/pdf/main_combined.pdf. The approved review PDF is
output/pdf/sections4_5_shortening_review.pdf.

This folder contains the reviewed LaTeX inputs. Existing figures, reference
files and sections/o3_source_references.tex are shared with the other reports.
No file outside this repository is required for compilation. The corrected
O1 review figure is included in figures/o1_indices_review.pdf in this folder.

The old sections/section4_combined.tex, section5_combined.tex,
section6_combined.tex and appendices/combined_supporting_material.tex remain
available as historical sources. main_combined.tex no longer loads them.
Edit the inputs named in main_combined.tex when updating the combined report.
Do not append the old combined sections, which would duplicate content.
Individual authors' reports, including main.tex, have not been changed.

Pending writing remains pending, including the abstract, conclusion,
group limitations and other members' contribution entries. The body through
the conclusion is still longer than the target of 17 pages.

Local generation helpers and intermediate audit files outside the repository
are not required to build these frozen reviewed sources and were not imported.
