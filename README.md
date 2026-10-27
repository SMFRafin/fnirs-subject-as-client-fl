# Subject-as-Client Federated Learning for Calibration-Free Mental Workload Decoding from Wearable fNIRS

Code and results for the manuscript. Dataset: Tufts fNIRS2MW (https://tufts-hci-lab.github.io/code_and_datasets/fNIRS2MW.html), not included.

- `fed-workload-nirs.ipynb`: full pipeline, run top to bottom (Kaggle, NVIDIA T4). Finished runs are cached and skipped on restart.
- `results/`: one JSON record per experiment.
- `revision/`: CSVs from the revision analyses (equivalence tests, calibration tests and spans, sweep, normalisation-off, partition composition, split definitions).
- `tables/`, `figures/`: generated tables and figures.
- `manifest.json`: run manifest.