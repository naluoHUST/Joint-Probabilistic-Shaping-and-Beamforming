# Joint Probabilistic Shaping and Beamforming for MISO VLC Systems

This repository contains the official Python implementation of the algorithm proposed in the paper:

**"Joint Probabilistic Shaping and Beamforming Scheme for MISO VLC Systems"**

## 📌 Overview

The goal of this work is to jointly optimize:
- The **probability distribution** (`p*`) of the input symbols (probabilistic shaping),
- And the **beamforming vector** (`w*`) at the MISO VLC transmitter,

in order to **maximize mutual information** under average power and non-negativity constraints.

The simulation includes:
- Mutual information computation,
- Alternating optimization for `p` and `w`,
- 3D visualization of the optimized beamforming weights.



