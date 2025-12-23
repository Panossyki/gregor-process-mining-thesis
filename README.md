# Gregor Process Mining (Thesis Code)

This repository contains the code/notebooks used in my thesis to:
- Transform raw microservice JSON logs into an event log (CSV/XES)
- Perform process discovery (Alpha / Inductive / Heuristics miners) with PM4Py
- Run conformance checking (Token-Based Replay, Alignments where applicable)
- Extract performance KPIs (throughput per case, task durations, fixture waiting times)
- Generate the figures/tables reported in the thesis

## Repository structure (suggested)
- `notebooks/` : main Jupyter/Colab notebook(s)
- `figures/`   : exported plots (Petri nets, throughput, bottlenecks, etc.)
- `data/`      : input data (NOT included by default)
- `outputs/`   : generated CSV/XES/PNG outputs (optional)

## Requirements
Python 3.9+ is recommended.

Install dependencies:
```bash


