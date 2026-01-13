# Helical Coding Challenge — Scaling In-Silico Perturbation Inference

This repository contains a Jupyter notebook benchmarking naive per-cell vs batched inference for Geneformer in-silico perturbations using the Helical yolksac dataset.

## Contents

- In-silico perturbation generation
- Baseline: naive per-cell inference
- Optimization: batched inference and batch-size scaling analysis
- Correctness validation: embedding equivalence vs baseline
- Results summary: runtime, throughput, and peak GPU memory

## How to run

The notebook includes saved outputs from a GPU run for inspection.

To reproduce the results, open `HelicalCodingChallenge.ipynb` in Google Colab, switch the runtime to **GPU**, and run all cells top-to-bottom.

