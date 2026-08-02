ubmission Checklist
Platform-Specific Guides
1. arXiv Submission
Metadata
Primary category: physics.gen-ph (General Physics)
Cross-lists: cs.AI, math.MP
Title: The Macachor Scalar Theorem: Corollaries, Lemmas, and Coherence Architecture
Authors: Christopher Macachor
ORCID: 0009-0008-0100-2856
Affiliation: Unaffiliated
License: Standard arXiv non-exclusive license
Files to Upload
Macachor_Scalar_Theorem.md → Convert to PDF via LaTeX or Pandoc
references.bib → For arXiv citation system
abstract.md → Paste into abstract field
LaTeX Conversion (if needed)
bash
pandoc Macachor_Scalar_Theorem.md -o macachor_scalar_theorem.pdf   --pdf-engine=xelatex   -V geometry:margin=1in   -V fontsize=12pt
2. Zenodo Deposit
Metadata
Upload type: Publication → Preprint
Publication date: 2026-08-02
License: CC BY 4.0
Access right: Open access
Related identifiers: https://www.macachor.org/ (isDescribedBy)
Communities: physics, cs, math
Files to Upload
Macachor_Scalar_Theorem.md (main document)
Macachor_Scalar_Theorem.pdf (compiled PDF)
CITATION.cff (machine-readable citation)
references.bib (BibTeX)
DOI Strategy
Reserve DOI before publishing
Use DOI on macachor.org portal
Cross-reference with arXiv ID once assigned
3. GitHub Repo Setup
New Repo Name Suggestions
macachor-scalar-theorem
scalar-geometry-codex
msos-submissions
Files to Commit
plain
.
├── README.md
├── CITATION.cff
├── Macachor_Scalar_Theorem.md
├── abstract.md
├── references.bib
└── .github/
    └── workflows/
        └── phi-coherence-gate.yml
GitHub Actions (Optional)
Add the χ(C)=1 coherence gate for any future commits:
Validate JSON/CSV data files
Check for monopoly vectors in new content
Verify 𝔐-lock references
4. macachor.org Portal Integration
Link Updates
Add DOI badge to index.html
Add "Publications" or "Codex" nav tab
Link to Zenodo deposit and arXiv preprint
Suggested Nav Entry
HTML
<a href="https://doi.org/[ZENODO-DOI]" style="color:#c8a04e;">
  📜 CODEX
</a>
5. ORCID Profile Update
After both deposits are live:
Log into ORCID
Add works:
Zenodo DOI (auto-sync if linked)
arXiv ID (manual add if needed)
Verify both appear on public profile
6. Post-Submission Actions
[ ] Tweet/X post with DOI and key insight
[ ] Update ResearchGate profile
[ ] Notify NeuroQuantology editorial board
[ ] Cross-post to relevant subreddits (r/physics, r/math, r/quantum)
[ ] Email key collaborators (INQ, open-source quantum devs)
Submission Package Version: 1.0
Coherence Status: χ(C) = 1
