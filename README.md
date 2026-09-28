# LatentGAT Segmentation

Research pages for a 3D U-Net + Graph Attention Network (Custom3DUNet_LatentGAT) brain tumor segmentation model, trained on BraTS2021.

**Live site:** https://muhammad-azeem-bhatti.github.io/latentgat-training-dashboard/ — landing page with links to all three pages below.

**Training dashboard:** https://muhammad-azeem-bhatti.github.io/latentgat-training-dashboard/training.html — per-epoch training-metrics chart (Dice, HD95, NSD, Sensitivity, Precision, Specificity — mean and per-region) across the full 200-epoch run.

**Generalization comparison:** https://muhammad-azeem-bhatti.github.io/latentgat-training-dashboard/generalization-comparison.html — the same metric suite comparing the epoch-156 checkpoint on the home BraTS2021 validation split against two out-of-distribution BraTS-Africa cohorts and a second glioma cohort, UCSF-PDGM (n=239 patients not present in BraTS2021, plus a whole-dataset leakage diagnostic), all with identical 4-view-TTA inference. Includes a region-aware table for regions absent from the ground truth.

**BraTS2021 deep dive:** https://muhammad-azeem-bhatti.github.io/latentgat-training-dashboard/results.html — training curve, per-patient Dice/HD95/NSD distribution across all 251 home validation patients, a voxel-level confusion matrix, and qualitative segmentation figures for the 5 best- and 5 worst-segmented cases.

Four self-contained HTML pages, no build step or dependencies beyond a Google Fonts stylesheet.
