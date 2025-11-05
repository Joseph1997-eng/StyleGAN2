# 🎨 StyleGAN2 — Components and Implementation with PyTorch

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Joseph1997-eng/StyleGAN2/blob/main/StyleGAN2.ipynb)

## 📘 Overview
This repository provides an educational implementation of **StyleGAN2**, one of the most advanced and popular Generative Adversarial Networks (GANs) for high-quality image synthesis.

The notebook (`StyleGAN2.ipynb`) demonstrates key internal mechanisms that make StyleGAN2 powerful — including **style mapping**, **adaptive instance normalization (AdaIN)**, **noise injection**, and **style mixing**.  
This is based on the assignment and coursework from *"Build Better Generative Adversarial Networks (GANs)"* on Coursera (DeepLearning.AI).

---

## 🧩 Contents
- `StyleGAN2.ipynb` — Main notebook with complete code and explanations  
- `droplet_artifact.png` — Visualization of common GAN droplet artifacts  
- `noise_contributions.png` — Example of noise effects in intermediate layers  
- `stylegan_architectures.png` — StyleGAN2 architecture overview  
- `gaugan_in.png` — Input visualization for style modulation

---

## 🚀 Features
- Implementation of key **StyleGAN2 components** in PyTorch
- Hands-on demonstration of:
  - **Mapping network** and latent space exploration  
  - **AdaIN normalization** and feature control  
  - **Noise injection** for fine-grained stochastic details  
  - **Style mixing** and hierarchical style influence  
- Visual analysis of generated image styles and artifacts  

---

## 🧮 Model Architecture
StyleGAN2 improves on traditional GANs with a **two-stage mapping** process:
1. **Mapping Network** — Transforms the input latent vector `z` into an intermediate latent space `w`.
2. **Synthesis Network** — Uses `w` to control styles at each layer via **AdaIN**, allowing disentangled feature control.

Additional improvements include:
- **Path length regularization**
- **Weight demodulation**
- **Elimination of droplet artifacts**

---

## 🧰 Requirements
- Python ≥ 3.8  
- PyTorch ≥ 2.0  
- NumPy  
- Matplotlib  
- Jupyter Notebook or Google Colab  

---

## ▶️ Run on Google Colab
You can run this notebook directly on Google Colab by clicking the badge below:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Joseph1997-eng/StyleGAN2/blob/main/StyleGAN2.ipynb)

---

## 🧑‍💻 How to Use

### Clone the Repository
```bash
git clone https://github.com/Joseph1997-eng/StyleGAN2.git
cd StyleGAN2
