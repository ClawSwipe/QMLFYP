# Evaluating Initialization Strategies in Hamiltonian-Embedded Quantum Neural Networks

## Overview
This repository contains the code and data used in the research paper:
**"Evaluating Initialization Strategies in Hamiltonian-Embedded Quantum Neural Networks"**

This study investigates the impact of different initialization strategies—Random, Beta, and a weighted ensemble approach—on the performance of Hamiltonian-embedded Quantum Neural Networks (QNNs) across four datasets: Kaggle CT Medical Images, SKlearn Digits, MNIST, and FashionMNIST.

## Methodology
The study utilizes **Hamiltonian embedding** to encode classical image data into quantum states. The quantum model incorporates **data reuploading circuits**, allowing for repeated exposure of quantum states to the same data, enhancing feature extraction.

Three initialization strategies are evaluated:
- **Random Initialization**: Parameters are randomly assigned values in the range [0,1].
- **Beta Initialization**: Parameters are sampled from a Beta distribution to mitigate barren plateaus.
- **Ensemble Approach**: A weighted average of Random and Beta initialization strategies is used to optimize performance.

Each initialization method is tested across four datasets, and results are compared based on training loss, validation accuracy, and generalization performance.

## Repository Structure
```
├── ct-med-img/                # Kaggle CT Medical Images dataset
├── mnist/                     # MNIST dataset
├── fashion-mnist/             # Fashion-MNIST dataset
├── sklearn-digits-dataset/    # SKlearn Digits dataset
├── README.md                  # This document
```
Each dataset directory contains:
- **Code files** for training and evaluation
- **CSV files** with recorded model weights
- **Graphs** illustrating experimental results

## Acknowledgments
We acknowledge the support of FAST National University of Computer and Emerging Sciences (NUCES), Karachi, Pakistan, and the contributions of our research team.

