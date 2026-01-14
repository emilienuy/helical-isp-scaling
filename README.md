# Helical Coding Challenge — Scaling In-Silico Perturbation Inference

This repository contains my solution to the **Helical coding challenge on scaling in-silico perturbation inference**, built using the open-source **Helical** package and the Geneformer model.

The notebook benchmarks **naive per-cell inference vs batched inference** for Geneformer in-silico perturbations using the Helical yolksac dataset, with a focus on reducing inference time while preserving output correctness.

Helical repository: https://github.com/helicalAI/helical

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/emilienuy/helical-isp-scaling/blob/main/isp_scaling_challenge.ipynb)

## Contents

- In-silico perturbation generation
- Baseline: naive per-cell inference
- Optimization: batched inference and batch-size scaling analysis
- Correctness validation: embedding equivalence vs baseline
- Results summary: runtime, throughput, and peak GPU memory

## How to run

Open `HelicalCodingChallenge.ipynb` in Google Colab.

The notebook includes saved outputs from a GPU run for inspection.

To reproduce the results, switch the runtime to **GPU**, and run all cells top-to-bottom.

