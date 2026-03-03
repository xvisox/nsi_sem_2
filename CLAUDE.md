# Fine-Grained Early Stopping — Reveal.js Presentation

## Project
ML seminar presentation (30 min, master's level) on two papers about fine-grained early stopping.

## Papers
- **Paper 1 (IES):** "Instance-Dependent Early Stopping" — Yuan et al., ICLR 2025 (`papers/p1.pdf`)
  - Per-sample stopping via second-order loss differences
- **Paper 2 (GradES):** "GradES: Significantly Faster Training in Transformers with Gradient-Based Early Stopping" — Wen et al., 2025 (`papers/p2.pdf`)
  - Per-matrix stopping via gradient-change magnitudes

## Files
- `presentation.html` — Main presentation (12 slides, inline CSS, MathJax4)
- `images/` — 6 extracted figures from PDFs (ies-fig1/3/4, ies-algo1, grades-fig1/2)
- `papers/` — Source PDFs

## Tech Stack
- Reveal.js with `white.css` theme
- MathJax4 for formulas (`\[...\]` display, `\(...\)` inline)
- Plugins: RevealMath.MathJax4, RevealNotes, RevealZoom
- Resolution: 1920x1080 (16:9), slide numbers `c/t`

## How to View
Open `presentation.html` in a browser (works with `file://` protocol). Press `S` for speaker notes.

## Figure Extraction
Figures extracted with PyMuPDF (`fitz`) at 300 DPI from specific page regions. See extraction script in conversation history if re-extraction is needed.
