# Multi-Heuristic A* for Mars Rover Navigation

An ablation study evaluating the role of heuristic diversity in Multi-Heuristic A* (MHA*) within cost-aware, synthetic Mars-like terrain maps.

## Overview
This project deconstructs the MHA* algorithm to determine if its performance gains stem from its multi-queue architecture or the diversity of its heuristics. 

### Key Features
- [cite_start]**Planners Implemented:** Weighted A* (WA*), MHA* with Diverse Heuristics, and MHA* with Homogeneous Heuristics[cite: 415, 437].
- [cite_start]**Heuristics Used:** Euclidean (Anchor), Scaled Manhattan, and Aggressive Euclidean[cite: 504, 505, 506].
- [cite_start]**Custom Terrain Model:** Synthetic 100x100 grid maps with varying traversal costs for Bedrock, Gravel, and Sand[cite: 466, 467, 468, 475].

## Results
[cite_start]Experiments across 500 scenarios show that MHA* with diverse heuristics achieves orders-of-magnitude reductions in node expansions and planning time compared to WA* in complex terrains[cite: 416].

## Requirements
- Python 3.x
- NumPy
- Matplotlib
- Seaborn
- SciPy

## Usage
Run the `mars_navigation_planner.ipynb` notebook to generate the terrain data, execute the path-planning experiments, and visualize the performance metrics.
