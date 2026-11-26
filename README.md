# Fundamentals of Full Waveform Inversion (FWI)

An interactive short course on acoustic wave propagation, inverse problems, gradients, numerical FWI and frequency continuation using GeoFWI velocity models.

## Interactive notebooks

| Notebook | Run |
|---|---|
| 01 — Seismic Wave Propagation | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aaspip/course-FWI-basics/blob/main/01_wave_propagation.ipynb) |
| 02 — Seismic Forward and Inverse Problems | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aaspip/course-FWI-basics/blob/main/02_forward_inverse.ipynb) |
| 03 — FWI Gradient and Optimization | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aaspip/course-FWI-basics/blob/main/03_fwi_gradient.ipynb) |
| 04 — Full Waveform Inversion: Numerical Examples | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aaspip/course-FWI-basics/blob/main/04_fwi_example.ipynb) |
| 05 — Cycle Skipping and Multiscale FWI | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aaspip/course-FWI-basics/blob/main/05_multiscale_fwi.ipynb) |

## Running in Colab

1. Sign in to Google and open a notebook using its badge.
2. Optionally select Runtime → Change runtime type → GPU. CPU is supported.
3. Connect and run cells sequentially (Shift+Enter), including setup and data retrieval.
4. Save a personal copy using File → Save a copy in Drive.

A modern browser and internet connection are required; no local installation is needed. Dependencies are installed if missing. The loader attempts byte-range access to the official GeoFWI archive; if unsupported, it downloads approximately 2 GB. A fresh session may repeat downloads. If retrieval fails, retry or place the official `geofwi.npy` in `geofwi_cache/`.

The exercises use small 2-D acoustic models and an explicit differentiable solver. GPU availability and execution time depend on Colab resources.

## Data and references

- [GeoFWI dataset](https://doi.org/10.5281/zenodo.18603709)
- [Li et al. (2026), GeoFWI](https://doi.org/10.1029/2025JH001037)
- [Tarantola (1984), Inversion of seismic reflection data in the acoustic approximation](https://doi.org/10.1190/1.1441754)
- [Virieux and Operto (2009), An overview of full-waveform inversion in exploration geophysics](https://doi.org/10.1190/1.3238367)

[Course website](https://aaspip.github.io/course-FWI-basics/)
