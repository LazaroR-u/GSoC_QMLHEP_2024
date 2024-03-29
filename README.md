# GSoC ML4SCI-QMLHEP 2024
This repository contains a series of evaluation tasks as part of my application to the Google Summer of Code 2024 program, under the Machine Learning For Science organization (ML4SCI), within the Quantum Machine Learning in High Energy Physics program (QMLHEP). Specifically, the tasks are related to the projects "Equivariant Quantum Neural Networks for High Energy Physics Analysis at the LHC" and "Implementation of Quantum Generative Adversarial Networks to Perform High Energy Physics Analysis at the LHC". Below is a comprehensive overview of the tasks completed:

## Task I: Quantum Computing
For this task, two simple quantum circuits were constructed using basic gates such as Hadamard, CNOT, Rotations, and SWAP. These circuits were implemented using Cirq and Pennylane.

## Task II: Classical Graph Neural Network (GNN)
Utilizing ParticleNet's dataset for quark/gluon jet classification, the following activities were performed:

Selection of 2 graph-based architectures to classify jets as quarks or gluons. A detailed description of the considerations taken to project this point-cloud dataset to a set of interconnected nodes and edges was provided.
Discussion of the resulting performance of the 2 chosen architectures.

## Task III: Open Task
This task shared a general perspective on quantum computing and quantum machine learning. Comments were provided on personal experiences, quantum algorithms, and suggested methodologies.

## Task IV: Quantum Generative Adversarial Network (QGAN)
Exploration was conducted using a quantum generative adversarial network (QGAN) to solve a high-energy data analysis issue, particularly separating signal events from background events. This task utilized the Google Cirq and Tensorflow Quantum (TFQ) libraries. Demonstrations were made on fine-tuning machine learning models to improve performance, evaluated with classification accuracy or Area Under ROC Curve (AUC).

## Task VII: Equivariant Quantum Neural Networks
An implementation of a $\mathbb{Z}_2 \times \mathbb{Z}_2$ equivariant quantum neural network (EQNN) was completed. A classification dataset with two classes and two features, respecting the $\mathbb{Z}_2 \times \mathbb{Z}_2$ symmetry (mirror symmetry along y=x), was generated. Both QNN and EQNN were trained to solve the classification problem.

For further details on each task and its implementation, please refer to the corresponding files in this repository.
