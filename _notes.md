# Revision Notes

Track what you've added, removed, or rewritten here.

## 2026-05-12 — Running Project added: "Synthesize a Target Molecule"

Generated 31 end-of-chapter LLM Exercise blocks via the Running Project Exercise Generator. Project selected: **Synthesize a Target Molecule** — student picks a real drug, natural product, or industrial chemical in Ch 1 and develops a complete retrosynthetic + forward synthesis across the 31 chapters. Final deliverable: 5,000-8,000 word synthesis document with mechanism arrows, predicted spectra, and literature comparison.

The architecture mirrors the book's content arc. Chs 1-5 analyze the target's structure (bonds, acid-base sites, stereochemistry). Chs 6-11 set up the retrosynthesis logic and propose C-C-bond-forming steps. Chs 12-14 predict spectra (MS/IR/NMR/UV) for verification. Chs 15-16 handle aromatic chemistry. Chs 17-24 install functional groups by class. Chs 25-29 cover biomolecule classes (carbohydrates, peptides, lipids, nucleic acids, metabolic fate). Ch 30 covers pericyclic reactions. Ch 31 compiles the final document and compares to published literature.

Each chapter's prompt does one of three things based on whether the chapter's chemistry applies to the chosen target:
- **Structural analysis**: if the chapter's framework illuminates part of the target.
- **Synthetic step**: if the chapter's reactions install or transform a functional group in the synthesis.
- **Non-application**: if the chapter doesn't apply (e.g., nucleic acid chapter for a small-molecule drug), the student explains why it doesn't apply — itself a useful learning exercise.

Methodological commitments baked in: every step has mechanism arrows; every stereocenter is tracked; every alternative disconnection considered must be explicitly rejected and named; the Ch 31 final document REQUIRES comparison to published synthesis (this is the project's most valuable learning). The book.md's stated skeptical-curious LLM posture is honored: prompts often note "verify LLM-generated pKa/spectra against literature" rather than trusting raw LLM output.

Most consequential single chapter: Ch 1 (target selection). Bad targets — molecules with no published synthesis, too-simple structure, or no biological/industrial significance — produce bad projects. The Ch 1 prompt requires the student to find a published synthesis FIRST, before committing.

Tool recommendations: Claude Project as the home for the building document; Claude chat for individual analyses; Cowork for Ch 31 final compilation; occasional Claude Code for any computational chemistry sanity-checks. ChemDraw or MarvinSketch optional but useful for clean structure drawings.

Each block appended to the bottom of its chapter file. Total addition: ~25,000 words of new content across 31 chapters.

**Known follow-up for review:** the biomolecule chapters (25-28) are calibrated to whether the target is biological. For small-molecule drugs, those chapters become brief "doesn't directly apply" sections. If the workshop wants those chapters to make a stronger contribution for non-biomolecule targets, the prompts could be retuned to require pseudo-biomolecule analysis (e.g., "even though your target isn't a carbohydrate, find a sugar-like feature anywhere in its 3D shape that affects bioactivity").

**Honest LLM-as-mechanism-predictor caveat:** the book.md states "LLMs are particularly weak [at spectroscopy]." Chs 12-13 (MS/IR and NMR) honor this — they instruct students to verify LLM-generated chemical shifts against published spectra. The pattern is repeated in Ch 5 (R/S assignment, where LLMs often confuse CIP priorities), Ch 11 (mechanism predictions for less-common substrates), and Ch 24 (heterocycle synthesis). Students who run these prompts will see real LLM failures — which is itself the chapter's pedagogical point.
