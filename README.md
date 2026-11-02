# Security Analysis of AES-128 Against Fault Injection Attacks

## Project Overview

This project investigates the security of AES-128 encryption against fault injection attacks using RTL simulation and machine learning techniques.

The project focuses on injecting controlled faults into selected AES execution rounds, observing their effects on internal encryption states and ciphertext outputs, and analysing fault propagation.

## Objectives

- Study AES-128 encryption architecture and round transformations.
- Implement an RTL-based fault injection mechanism.
- Analyse fault propagation across AES rounds.
- Generate datasets from simulation outputs.
- Apply machine learning techniques to analyse and classify fault-related behaviour.
- Evaluate the impact of fault injection on AES hardware security.

## Technologies Used

- Verilog HDL
- Xilinx Vivado
- Python
- Pandas
- NumPy
- Scikit-learn
- Machine Learning

## Methodology

1. AES-128 RTL implementation and verification.
2. Controlled XOR-based fault injection at selected rounds.
3. Simulation and collection of faulty states and ciphertext outputs.
4. Dataset generation and feature extraction.
5. Machine learning-based fault analysis.
6. Evaluation of fault propagation and classification performance.

## Machine Learning

A Random Forest classifier is used to analyse fault-related features and investigate fault detection and classification.

## Project Status

Completed – experimental results and implementation details will be documented in the repository.

## Repository Structure

The source code, simulation files, datasets and analysis results will be organised into separate directories.

## Author

Rakshitha V
