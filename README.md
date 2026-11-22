# Millimeter-Isotropic Tokens: 3D Vision Transformers for Small csPCa Lesion Detection in Anisotropic bpMRI

Ronald Marca, Paola Caprile, Rodrigo Salas, Cecilia Besa. Work in progress, iHEALTH 2026.

**Page:** https://marquita-oss.github.io/small-lesion-vit/

Pretrained 3D vision transformers beat CNNs overall on PI-CAI but find less than half as many lesions spanning
1–2 slices. Making the token isotropic in millimeters (24 × 4 × 4 mm → 6 × 8 × 8 mm), with nothing else changed,
made the model worse everywhere: the bottleneck is in-plane detail, not z.

## Contents

| File | What it is |
|---|---|
| `index.html` | Project page (GitHub Pages, served from `main`) |
| `iHEALTH2026_slides.pdf` | Rapid-fire talk slides |
| `iHEALTH2026_poster.pdf` | Poster, 90 × 120 cm |
| `fig/` | Poster figures used on the page |
| `fig/people/` | Author photos (from each author's public institutional or GitHub profile) |

Code: coming soon, together with the full paper.

Data: PI-CAI public development set (Saha et al., Lancet Oncol 2024; CC BY-NC 4.0). Images on the page come from
that set. The PI-CAI test set was not used.

Funded by ANID, Millennium Science Initiative Program, ICN2021_004.
