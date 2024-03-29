# GSoC ML4SCI-QMLHEP 2024

This repository contains a series of evaluation tasks as part to participate in the Google Summer of Code 2024 program, in the Machine Learning For Science organization (ML4SCI), within the Quantum Machine Learning in High Energy Physics program (QMLHEP), especificly in the projects of "Equivariant Quantum Neural Networks for High Energy Physics Analysis at the LHC" and "Implementation of Quantum Generative Adversarial Networks to Perform High Energy Physics Analysis at the LHC". Below is a brief description of the tasks addressed:

## Task I: Quantum Computing

In this task two simple quantum circuits with basic gates as Hadamard, CNOT, Rotations, SWAP and SWAP test were constructed using Cirq and Pennylane.

## Task II: Classical Graph Neural Network (GNN)

ParticleNet's dataset was used for quark/gluon jet classification, with the following activities performed:
- Selection of 2 graph-based architectures to classify jets as quarks or gluons. A description of the considerations taken to project this point-cloud dataset to a set of interconnected nodes and edges is provided.
- Discussion of the resulting performance of the 2 chosen architectures.

## Task III: Open Task

In this task, I give some comments on quantum computing and quantum machine learning. Comments on some experience, quantum algorithm, and suggested methods were given.

## Task IV: Quantum Generative Adversarial Network (QGAN)

Exploration of how to apply a quantum generative adversarial network (QGAN) to solve a high-energy data analysis issue, specifically, separating signal events from background events. The Google Cirq and Tensorflow Quantum (TFQ) libraries are used for this task. Understanding how to fine-tune your machine learning model to improve performance is demonstrated, evaluated with classification accuracy or Area Under ROC Curve (AUC).

## Task VII: Equivariant Quantum Neural Networks

A $\mathbb{Z}_2 \times \mathbb{Z}_2$ equivariant quantum neural network is implemented. A classification dataset with two classes and two features that respects the $\mathbb{Z}_2 \times \mathbb{Z}_2$ symmetry (mirror symmetry along y=x) is generated. QNN and EQNN are trained to solve the classification problem.

For more details on each task and its implementation, please refer to the corresponding files in this repository.
