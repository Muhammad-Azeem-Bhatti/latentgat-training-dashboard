# Training Dashboard

Training-metrics chart (Dice, HD95, NSD, Sensitivity, Precision, Specificity — mean and per-region) for a 3D U-Net + Graph Attention Network brain tumor segmentation model.

**Live page:** https://muhammad-azeem-bhatti.github.io/latentgat-training-dashboard/

**Generalization comparison:** https://muhammad-azeem-bhatti.github.io/latentgat-training-dashboard/generalization-comparison.html — the same metric suite comparing the epoch-156 checkpoint on the home BraTS2021 validation split against two out-of-distribution BraTS-Africa cohorts and a second glioma cohort, UCSF-PDGM (n=74 patients not present in BraTS2021), all with identical 4-view-TTA inference. Includes a region-aware table for regions absent from the ground truth.

Two self-contained HTML pages, no build step or dependencies beyond a Google Fonts stylesheet.
