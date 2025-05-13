# Deep neural networks for surface composition reconstruction from in situ exospheric measurements at Mercury
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15394849.svg)](https://doi.org/10.5281/zenodo.15394849)

This repository holds **all public versions** of our Mercury-exosphere manuscript
series.

| Version | Year | DOI | DNNs | Tasks | Datasets | Notes |
|---------|------|-----|------|-------|----------|-------|
| v0.0 | 2020 | 10.1088/1742-6596/1548/1/012014 | Testing three DNN types: MLP in one position, MLP in a 3x3 grid, and CNN in a 5x5 grid. | Mineralogy prediction (7 minerals) from exospheric elemental measurements. | Simulated dataset - very simplistic split and release processes (only MIV). | JPCS poster (supplement). Basic version |
| v1.0 | 2020 | Zenodo-assigned? | Testing three DNN types: single MLP with hyperparameter optimization, 2xMLP in series, 2xMLP in a simple decision-split. | Mineralogy (9 minerals) and elemental (11 elements) composition prediction  from exospheric elemental measurements; maps reconstruction and analysis. | Simulated dataset - simplistic split and release processes (4 main processes - MIV, SP, PSD, TD), no complex exospheric dynamics. | Complete study with simplified environment models, multiple processes, multiple networks, and multiple tasks introduction. |


**Quick links**

* **Latest PDF** → `docs/paper_v1.0__Kazakov_et_al_2020.pdf`   
* **Zenodo record (all versions)** → https://doi.org/10.5281/zenodo.15394849

### How to cite

Copy the snippet below (or use the `Cite this repository` button on GitHub):

### Repository structure

docs/ # Published PDFs

### Licensing

* **Text & figures**: Creative Commons **CC‑BY 4.0**  
* **Code**: MIT License

See `LICENSE.md` for the full terms.
