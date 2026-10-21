# EEGMI-Decoder

Algorithm repository for **An Efficient FPGA-Based SNN Accelerator for Motor-Imagery EEG Decoding with Online Euclidean Alignment**.

Yuanhang Li, Ahmed Sadaqa, Shun Li, Ankun Tian, Chao Chen, Ruiqi Chen, Bruno da Silva, and Ming Ling

**Manuscript status:** Under review at IEEE Transactions on Biomedical Circuits and Systems (TBioCAS).

## Project overview

The MI-EEG SNN Accelerator project combines a lightweight direct-coded spiking neural network (SNN) with a streaming FPGA accelerator for motor-imagery EEG decoding.

- The model uses input channel mixing and depthwise temporal spiking convolution, incorporating Online Euclidean Alignment to mitigate cross-session EEG drift.
- The accelerator exploits spike sparsity and logit-margin early exit to reduce data movement and unnecessary inference steps.

## Research implementation

The full research project uses **SystemVerilog and Python**, with **PyTorch and Vivado**. This repository is intended for the algorithm implementation.

## Code availability

Algorithm code release planned upon acceptance. This repository currently provides the project description; implementation files have not yet been released.

## Contact

Yuanhang Li: [yuanhangli@seu.edu.cn](mailto:yuanhangli@seu.edu.cn)
