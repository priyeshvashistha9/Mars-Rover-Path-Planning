# Multi-Heuristic A* for Mars Rover Navigation 🚀

An ablation study evaluating the role of heuristic diversity in Multi-Heuristic A* (MHA*) within cost-aware, synthetic Mars-like terrain maps.

## Overview
This project deconstructs the MHA* algorithm to determine if its performance gains stem from its multi-queue architecture or the diversity of its heuristics. 

### Key Features
- **Planners Implemented:** Weighted A* (WA*), MHA* with Diverse Heuristics, and MHA* with Homogeneous Heuristics.
- **Heuristics Used:** Euclidean (Anchor), Scaled Manhattan, and Aggressive Euclidean.
- **Custom Terrain Model:** Synthetic 100x100 grid maps with varying traversal costs for Bedrock, Gravel, and Sand.

## Results 📊
Experiments across 500 scenarios show that MHA* with diverse heuristics achieves orders-of-magnitude reductions in node expansions and planning time compared to WA* in complex terrains.

## Requirements
- Python 3.x
- NumPy
- Matplotlib
- Seaborn
- SciPy

## Usage
Run the `mars_navigation_planner.ipynb` notebook to generate the terrain data, execute the path-planning experiments, and visualize the performance metrics.
