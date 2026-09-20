# Training Dashboard

Live training-metrics chart (Dice, HD95, NSD, Sensitivity, Precision, Specificity — mean and per-region) for a 3D U-Net + Graph Attention Network brain tumor segmentation model.

**Live page:** _(will be at `https://<your-username>.github.io/<repo-name>/` once Pages is enabled)_

Single self-contained `index.html`, no build step or dependencies beyond a Google Fonts stylesheet. To update with new epochs, regenerate the embedded data block from a `training_metrics_history_*.csv` and copy the result in as `index.html`, then push.
