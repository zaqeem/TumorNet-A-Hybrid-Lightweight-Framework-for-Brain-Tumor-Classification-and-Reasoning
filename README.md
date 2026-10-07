# TumorNet: A Hybrid Lightweight Framework for Brain Tumor Classification and Reasoning

**Muhammad Zaqeem · Hanxiang Wang · Muhammad Fayaz · Defu Qiu · Sajjad Ahadzadeh · Tan N. Nguyen · L. Minh Dang**

[![Paper](https://img.shields.io/badge/Paper-Information%20Sciences-blue)](https://doi.org/10.1016/j.ins.2026.123423)
[![DOI](https://img.shields.io/badge/DOI-10.1016%2Fj.ins.2026.123423-green)](https://doi.org/10.1016/j.ins.2026.123423)

---

## Overview

TumorNet is a lightweight hybrid framework for brain tumor diagnosis from magnetic resonance imaging (MRI). It combines efficient convolutional feature extraction with MobileViT-based visual representation learning and attention-driven feature refinement. A reasoning component further provides an interpretable description of the model's diagnostic decision.

<p align="center">
  <img src="assets/framework.png" width="90%" alt="TumorNet Framework">
</p>

---

## Framework

TumorNet integrates complementary components within a unified architecture:

- **CNN Stem** for low-level visual feature extraction
- **Multi-Scale Feature Learning** for complementary spatial representations
- **MobileViT-XXS** for lightweight global representation learning
- **Squeeze-and-Excitation (SE)** for channel-wise feature refinement
- **Feature Fusion** for combining discriminative representations
- **Reasoning Module** for generating an interpretable diagnostic description

---

## Paper

**TumorNet: A Hybrid Lightweight Framework for Brain Tumor Classification and Reasoning**

*Information Sciences*, Volume 746, Article 123423, 2026.

**DOI:** [10.1016/j.ins.2026.123423](https://doi.org/10.1016/j.ins.2026.123423)

**Paper:** https://www.sciencedirect.com/science/article/pii/S0020025526003543

---

## Citation

```bibtex
@article{zaqeem2026tumornet,
  title   = {TumorNet: A Hybrid Lightweight Framework for Brain Tumor Classification and Reasoning},
  author  = {Zaqeem, Muhammad and Wang, Hanxiang and Fayaz, Muhammad and Qiu, Defu and Ahadzadeh, Sajjad and Nguyen, Tan N. and Dang, L. Minh},
  journal = {Information Sciences},
  volume  = {746},
  pages   = {123423},
  year    = {2026},
  doi     = {10.1016/j.ins.2026.123423}
}
