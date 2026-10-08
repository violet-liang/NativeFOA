# NativeFOA: Representation, Editing, and Benchmark for Spatial Audio

[![Project Page](https://img.shields.io/badge/Project-Page-13283a?style=for-the-badge&logo=githubpages&logoColor=white)](https://nativefoa.github.io/)
[![Audio Demos](https://img.shields.io/badge/Audio-Demos-c94246?style=for-the-badge&logo=soundcloud&logoColor=white)](https://nativefoa.github.io/)

## Overview

Spatial audio editing for immersive media requires jointly controlling semantic content and sound-field geometry while preserving the surrounding acoustic scene. To address these challenges, we introduce **NativeFOA**, a unified framework operating directly in the First-Order Ambisonics (FOA) domain.

For representation, **NativeFOA-VAE** introduces a novel spatial reconstruction objective that improves acoustic fidelity and spatial consistency. Building on this latent representation, **NativeFOA-Editor** leverages conditional flow matching to perform source trajectory modification, source removal, and source replacement while keeping the non-target sound field intact. To evaluate spatial editing systematically, we establish **NativeFOA-Bench** to jointly assess target spatial accuracy, audio fidelity, and non-target preservation.
