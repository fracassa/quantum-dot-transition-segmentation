# quantum-dot-transition-segmentation
A reduced replication of quantum-dot autotuning workflows, inspired by Kalantre et al. (2019) and Hader et al. (2025). The project compares Canny–Hough line detection with a compact U-Net to identify charge-transition lines in noisy simulated stability diagrams and extract interpretable slopes and intersections.

---

#### Quantum-Dot Transition Segmentation

## Status
Work in progress. No quantitative results are available yet.

## Objective
Develop a simulation-assisted pipeline for detecting charge-transition
lines in quantum-dot charge-stability diagrams.

The project compares an interpretable Canny–Hough baseline with a
compact U-Net segmentation model, then evaluates robustness under
controlled changes in noise and device parameters.

## Planned workflow
1. Load and inspect simulated diagrams and ground-truth labels.
2. Define the transition-segmentation task and dataset splits.
3. Implement a classical edge-detection baseline.
4. Train a compact U-Net.
5. Compare segmentation and line-localization performance.
6. Evaluate robustness under controlled distribution shifts.
7. Optionally inspect predictions on experimental diagrams.

## Scope
This is an educational study inspired by quantum-dot characterization
and autotuning research. It does not demonstrate autonomous tuning,
experimental readout performance, or validated device-parameter
extraction.

## References
Paper references and exact reproduction scope will be documented
after the dataset and baseline experiment are selected.
