# MSc Dissertation: Spatial distribution of sleep spindles and thalamocortical and hippocampal network connections in mice
**Author:** Daniel Dehghan Ortekand  
**Supervisor:** Dr. Maryam Ghorbani  
**Institution:** Ferdowsi University of Mashhad (one of the best universities in Iran), Faculty of Engineering  
**Date:** February 2024  

---

## 📖 Abstract

Neural information exchange occurs both spatially and temporally. The coupling between sleep spindles and slow oscillations reflects inter-network communications and the memory consolidation process. This study investigates the spatial distribution of brain oscillations and their propagation using Local Field Potential (LFP) data recorded from mice. 

Key contributions of this research include:
- Separation and categorization of sleep spindles into **local** and **global** groups, and slow oscillations into **single-peaked** and **double-peaked** groups.
- Demonstration of a significant correlation between neuronal activity and sleep events (spindles and slow oscillations).
- Phase-Amplitude Coupling (PAC) analysis revealing significant phase differences between thalamic propagation events.
- Investigation of the relationship between the hippocampus and thalamus regions, showing significant phase correlation between global/local sleep spindles and hippocampal ripples.

**Keywords:** Sleep wave propagation, LFP, Sleep spindles, Slow oscillations, Sleep neurophysiology.

---

## 📂 Repository Contents

This repository contains the complete LaTeX source code and assets used to compile the dissertation.

```text
├── main.tex                  # Main LaTeX document
├── References.bib            # Bibliography database
├── logo.png                  # University logo (used in title page)
├── fig*.png / fig*.jpg       # All figures and plots referenced in the text
└── README.md                 # This file

⚙️ Prerequisites
To compile this document locally, you will need a full LaTeX distribution installed on your system:
TeX Live (Linux/Windows) or MacTeX (macOS)
A LaTeX editor such as TeXstudio, VS Code (with the LaTeX Workshop extension), or Overleaf (online).
The document uses standard packages (geometry, graphicx, amsmath, hyperref, caption, etc.) and the IEEEtran bibliography style.

🛠️ How to Compile
Option 1: Overleaf (Recommended for ease of use)
Go to Overleaf and create a new blank project.
Upload main.tex, References.bib, and all image files to the project.
Ensure the compiler is set to pdfLaTeX (Menu → Compiler → pdfLaTeX).
Click Recompile.

Option 2: Local Compilation (Command Line)
Navigate to the repository directory in your terminal and run the following commands:
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
This sequence ensures that all cross-references, the table of contents, and the bibliography are correctly generated.

📬 Contact
For questions, collaborations, or inquiries regarding the code and methodology, please feel free to reach out:
Email: [Daniel.Dehghan.Ortekand@gmail.com]
GitHub: [https://github.com/Daniel-Dehghan-Ortekand]
