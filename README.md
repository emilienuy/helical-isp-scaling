# Helical Coding Challenge — Scaling In-Silico Perturbation Inference

This notebook benchmarks naive per-cell vs batched inference for Geneformer in-silico perturbations using the Helical yolksac dataset.

## Contents
- Data Perturbations
- Baseline: naive per-cell loop
- Optimization: batched inference + batch-size scaling analysis
- Correctness validation: embedding equivalence vs baseline
- Results summary: runtime, throughput, peak GPU memory

## How to run
The notebook includes saved outputs from a GPU run for inspection.

To reproduce the results:
1. Open `HelicalCodingChallenge.ipynb` in Google Colab.
2. Switch the runtime to **GPU**.
3. Run all cells top-to-bottom.

## Notes
The notebook includes saved outputs for inspection (tables/plots) from a GPU run.
