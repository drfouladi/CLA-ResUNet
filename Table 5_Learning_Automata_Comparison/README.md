# Table 5 – Learning Automata Comparison

This directory contains the experimental result files corresponding to **Table 5** of the manuscript:

> **CLA-ResUNet: Continuous Learning Automata for Small Liver Tumor Segmentation in CT Images**

## Description

The files in this folder contain the segmentation results used to generate:

**Table 5. Comparison of learning automata variants across baseline segmentation models (100 training epochs).**

Performance is reported as:

- Liver Dice Similarity Coefficient (DSC)
- Tumor Dice Similarity Coefficient (DSC)

The evaluated learning automata variants include:

- Classic Learning Automata (Classic LA)
- PLA
- Continuous Learning Automata (CLA)
- GLA
- DRLA
- HLA
- BLA
- ALRLA

The evaluated baseline segmentation models include:

- Attention U-Net
- UNet++
- ResUNet
- ResUNet + Attention
- ResUNet + Swin Transformer Encoder

## Dataset

- Dataset: LiTS 2017
- Training epochs: 100

## Purpose

These files are provided to support the experimental results reported in Table 5 and to improve the transparency and reproducibility of the manuscript.
