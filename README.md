# 🧪 GENERATIVE AI LAB EXPERIMENTS

> **A comprehensive laboratory course exploring cutting-edge generative AI architectures through practical implementations and interactive experiments**

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![PyTorch](https://img.shields.io/badge/PyTorch-2.11-red.svg)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.8-orange.svg)

---

## 📋 Overview

This workbook provides a **structured, hands-on journey** through the foundations and advanced techniques of generative AI. Designed for students and practitioners, it combines theoretical concepts with working code implementations across **10 comprehensive experiments** and a **capstone project**.

### What You'll Master

✨ **Distribution Sampling** — Generate and visualize random samples from probability distributions  
✨ **Parameter Estimation** — Master Maximum Likelihood Estimation (MLE) techniques  
✨ **Neural Networks** — Implement backpropagation and stochastic gradient descent from scratch  
✨ **Adversarial Training** — Build and train GANs with competing generator-discriminator architectures  
✨ **Invertible Models** — Design flow-based generative models using normalizing flows  
✨ **Latent Representations** — Explore variational autoencoders (VAE) and learned embeddings  
✨ **Sequential Generation** — Implement autoregressive models (PixelCNN) for pixel-by-pixel synthesis  
✨ **Performance Metrics** — Rigorously evaluate models using standard ML metrics  

---

## 🔬 Experiment Breakdown

| # | Experiment | Focus Area | Key Skills |
|---|-----------|-----------|-----------|
| 1 | **Random Sampling** | Probability Distributions | NumPy · Visualization · PDF comparison |
| 2 | **MLE** | Parameter Estimation | Optimization · Likelihood · Convergence |
| 3 | **Neural Networks** | Deep Learning | Backpropagation · SGD · PyTorch |
| 4 | **GANs** | Adversarial Training | Generator/Discriminator · Minimax objectives |
| 5 | **Normalizing Flows** | Invertible Models | Change-of-variables · Exact likelihood |
| 6 | **Evaluation Metrics** | Model Assessment | Accuracy · Precision · ROC-AUC · F1 |
| 7 | **Validation** | Generalization | Overfitting detection · Hyperparameter tuning |
| 8 | **VAE** | Latent Space | Reparameterization · ELBO · Embeddings |
| 9 | **PixelCNN** | Autoregressive Models | Masked convolutions · Sequential generation |
| 10 | **Loss Analysis** | GAN Dynamics | Convergence properties · Stability |
| 📁 | **Capstone** | Integration | Multi-distribution MLE · Error analysis |

---

## 🚀 Quick Start

### Installation (2 minutes)

```bash
# Clone repository
git clone <repository-url>
cd Gen_AI_Experiments

# Install dependencies
pip install numpy matplotlib scipy torch torchvision scikit-learn

# Launch notebook
jupyter notebook Generative_AI_Experiments.ipynb
```

### What You Get

✓ **10 Complete Experiments** — Theory + code + visualizations  
✓ **Production-Grade Code** — Best practices throughout  
✓ **Beautiful Visualizations** — Intuitive plots and diagrams  
✓ **Modular Design** — Run experiments independently  
✓ **Reproducible Results** — Fixed random seeds  

---

## 📦 Requirements

| Package | Version | Purpose |
|---------|---------|---------|
| **numpy** | 2.4.4+ | Numerical computing |
| **matplotlib** | 3.10+ | Data visualization |
| **scipy** | 1.17+ | Statistical distributions |
| **torch** | 2.11+ | Deep learning framework |
| **torchvision** | 0.26+ | Computer vision utilities |
| **scikit-learn** | 1.8+ | ML metrics & models |

---

## 💡 Key Features

🎯 **Progressive Learning** — Foundational → Advanced concepts  
🎯 **Hands-On Practice** — Write real implementations, not just theory  
🎯 **Professional Code** — Industry standards and best practices  
🎯 **Rich Visualizations** — Understand concepts through plots  
🎯 **Self-Contained** — Each experiment is independent  
🎯 **Well-Documented** — Clear explanations at every step  

---

## 🎓 Learning Path

```
START (Experiment 1)
  ↓
[Distributions] → [MLE] → [Neural Nets]
  ↓
[GANs] → [Flows] → [Evaluation]
  ↓
[Validation] → [VAE] → [PixelCNN]
  ↓
[Loss Analysis] → [Capstone Project]
  ↓
END (Ready for Advanced Research!)
```

---

## 📚 What You'll Implement

### Generative Models
- ✓ Maximum Likelihood Estimation (MLE)
- ✓ Generative Adversarial Networks (GANs)
- ✓ Normalizing Flows (RealNVP)
- ✓ Variational Autoencoders (VAE)
- ✓ Autoregressive Models (PixelCNN)

### Core Techniques
- ✓ Backpropagation & Gradient Descent
- ✓ Adversarial Training
- ✓ Invertible Transformations
- ✓ Latent Space Modeling
- ✓ Sequential Generation

---

## 🎯 Learning Outcomes

After completing this workbook, you'll be able to:

✅ **Understand** modern generative modeling paradigms and theory  
✅ **Implement** state-of-the-art architectures from first principles  
✅ **Debug** deep learning code systematically and effectively  
✅ **Evaluate** model performance using rigorous metrics  
✅ **Design** custom generative models for specific problems  
✅ **Read** and understand cutting-edge research papers  

---

## 💻 System Requirements

- **CPU**: Dual-core processor (2+ cores recommended)
- **RAM**: 4GB minimum (8GB+ recommended)
- **Storage**: 2GB for datasets and checkpoints
- **GPU**: Optional (NVIDIA for CUDA acceleration)
- **OS**: Windows, macOS, or Linux

---

## 📖 Detailed Experiment Descriptions

### Experiment 1: Generating Random Samples From Statistical Distributions
**Objective:** Learn probability distributions through sampling and visualization.  
**Output:** Histograms matching theoretical PDFs for Gaussian, Uniform, and Exponential distributions.

### Experiment 2: Estimating Parameters Through Maximum Likelihood
**Objective:** Master parameter recovery using MLE.  
**Output:** Parameter estimates with error analysis across sample sizes.

### Experiment 3: Training Deep Networks with Gradient Descent
**Objective:** Implement neural networks with backpropagation.  
**Output:** MNIST classifier with 97%+ accuracy and training curves.

### Experiment 4: Adversarial Training for Image Synthesis
**Objective:** Build and train a GAN.  
**Output:** Training dynamics showing convergence to Nash equilibrium.

### Experiment 5: Invertible Transformations for Density Estimation
**Objective:** Implement normalizing flows.  
**Output:** Generated samples matching complex distributions with exact likelihood.

### Experiment 6: Quantifying Model Performance With Standard Metrics
**Objective:** Comprehensive model evaluation.  
**Output:** Confusion matrices, ROC curves, and performance summaries.

### Experiment 7: Assessing Generalization: Validation Set Performance
**Objective:** Monitor overfitting and generalization.  
**Output:** Training vs. validation curves with gap analysis.

### Experiment 8: Latent Space Learning With Variational Autoencoders
**Objective:** Learn latent representations with VAE.  
**Output:** 2D latent space visualization with class clustering.

### Experiment 9: Sequential Image Synthesis with Autoregressive Models
**Objective:** Implement PixelCNN with masked convolutions.  
**Output:** Pixel-by-pixel image generation with causal ordering.

### Experiment 10: Comparing Loss Functions in Adversarial Training
**Objective:** Analyze GAN loss function variants.  
**Output:** Convergence comparison of BCE, Wasserstein, and feature matching losses.

### Capstone Project: Parameter Estimation for Probability Distributions
**Objective:** Integrate MLE across distributions.  
**Output:** Multi-distribution parameter recovery with convergence analysis.

---

**Happy Learning! 🧠✨**
