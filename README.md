# Less is More: Recursive Reasoning with Tiny Networks

## Overview
This repository contains the official documentation and code implementation for our submission to the **ARC Prize 2026 - Paper Track**. Our approach introduces a lightweight, recursive reasoning framework designed to adapt on the fly to novel, human-solvable visual grid transformations without relying on massive parameter scaling or heavy pre-training memorization.

## Key Features
- **Visual Perception Module:** A lightweight convolutional encoder that segments input grids into distinct object clusters based on color, adjacency, and symmetry.
- **DSL Generator:** Utilizes a specialized Domain-Specific Language (DSL) tailored for 2D grid manipulations rather than direct pixel-level predictions.
- **Recursive Refinement Loop:** Employs a tiny recurrent network that evaluates intermediate results against training examples dynamically, adjusting operational parameters until a complete match is achieved.

## Repository Structure
- `solution.py`: The core code implementing the recursive concept learner and visual perception module.
- `README.md`: Project description and documentation.

## Methodology
Instead of brute-force deep learning, our system mimics human cognitive processes by deconstructing grid puzzles into primitive shapes, applying recursive transformations, and verifying outcomes dynamically during inference.
