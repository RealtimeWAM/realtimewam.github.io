# RealtimeWAM project website

Public project page for **RealtimeWAM: How Fast Can I Run My World Action Model?**

- Website: https://realtimewam.github.io/
- Paper: https://arxiv.org/abs/2610.10079
- Code: https://github.com/Na2Ssss/RealtimeWAM

The page includes authors, robot demonstrations, paper results, the OpenWAM code release and a BibTeX citation. The anonymous project website is maintained separately.

## Preview

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000/`. This is a static website: no package installation or build step is required. Fonts, figures and videos are served locally; paper links point to arXiv. Results switch between backbones through native radio inputs and CSS, including when JavaScript is disabled.

## Publish

GitHub Pages serves the root of the `main` branch in `RealtimeWAM/realtimewam.github.io`. Push changes to `main` to update the public page. `.nojekyll` disables Jekyll processing.

Paper results cover FastWAM and OpenWAM. The linked code release currently implements the three RealtimeWAM components for OpenWAM.
