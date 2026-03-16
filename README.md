# 3T_1R Monograph

A browser-based tool for exploring all 256 variations of the 3T_1R algorithm.

**[Live demo →](https://3T_1R-Monograph.netlify.app)**

---

## The Algorithm

3T_1R — three triangles, one rotation — is a rule-based generative drawing system. Each iteration is defined by four parameters, each with four possible values derived from ratios in the Fibonacci sequence (23.6%, 38.2%, 61.8%, 76.4%):

- **T1** — point on the top edge → determines the base shape (cyanotype)
- **T2** — point on the bottom edge → accent triangle (green)
- **T3** — point on the right edge → accent triangle (purple)
- **R** — one of four 90° rotations applied to the whole composition

4 values × 4 parameters = **256 total combinations**.

Each iteration can be identified by its four-number code, e.g. `3, 3, 3, 4`. The underlying structure is retained regardless of size, colour, or medium.

The physical work is produced as cyanotype and ink on cotton rag. First shown at the GAS Members Show, 2025.

---

## The Explorer

A single HTML file, no dependencies, no build step.

**Single view** — adjust T1, T2, T3, and R individually with sliders. A randomize button lets you cycle through variations quickly. Configurable colour palette.

**Grid view** — all 256 variations displayed simultaneously. Adjustable cell size, toggleable cell spacing, and configurable loop order so you can explore how parameter relationships read across the full set. Click any cell to open it in single view.

---

## Usage

Download `3T_1R_explorer.html` and open it in any modern browser. No installation required.

---

## Licence

[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

You are free to share and adapt this work provided you:
- Give appropriate credit to **Stephen Boyd (@sspboyd)**
- Do not use it for commercial purposes
- Distribute any remixes under the same licence

---

## About

Stephen Boyd is a Toronto-based generative artist working in code since 2003. His practice centres on simple rule-based systems that produce emergent structure.

- Website: [sspboyd.ca](https://sspboyd.ca)
- Social: [@sspboyd](https://instagram.com/sspboyd)
