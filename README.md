**Neural Engine II: MNIST Implementation & Benchmarking**
_Part 2 of the Neural Engine Series_

This repository serves as the application and validation layer for the Neural Engine, a custom high-performance deep learning library written in Rust. While the core engine focuses on memory safety and low-latency execution, this project focuses on practical implementation, visualization, and performance benchmarking against standard datasets.

**Project Objectives**
Validation: rigorous testing of the Rust-based engine against real-world data, specifically the MNIST handwritten digit dataset.

Visualization: Analysis of learning curves, loss convergence, and prediction accuracy using Python-based data science tools.

Benchmarking: Performance comparisons between the custom Rust implementation and standard Python-based solutions.

_Repository Structure_
notebooks/ - Jupyter Notebooks containing the training logic, data loading, and visualization scripts.

data/ - Utilities for fetching and preprocessing the MNIST dataset (via TensorFlow/Keras or local binary parsing).

benchmarks/ - Scripts dedicated to measuring training speed and inference latency.
