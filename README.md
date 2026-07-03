# Generative Deep Learning with PyTorch

A collection of practical **Generative Deep Learning** projects implemented using **PyTorch**. This repository explores representation learning, synthetic image generation, and model robustness through Autoencoders, Generative Adversarial Networks (GANs), adversarial attacks, and modern generative modeling techniques. Each notebook has been reorganized, documented, and expanded to demonstrate practical deep learning workflows for generative AI.

![Autoencoder Architecture](http://kvfrans.com/content/images/2016/08/vae.jpg)

---

# 🚀 Repository Overview

This repository contains practical generative deep learning projects built with **PyTorch**, covering autoencoders, generative adversarial networks, adversarial robustness, and image generation through reproducible, well-documented notebooks.

---

# ✨ Project Highlights

- Autoencoders for unsupervised representation learning
- Convolutional Autoencoders
- Generative Adversarial Networks (GANs)
- Image generation from learned latent representations
- Adversarial attack techniques for evaluating model robustness
- GPU-ready training pipelines
- Well-documented notebooks suitable for learning and experimentation

---

# 📚 Topics Covered

- Autoencoders
- Convolutional Autoencoders
- Latent space representation learning
- Image reconstruction
- Generative Adversarial Networks (GANs)
- Generator and Discriminator architectures
- Synthetic image generation
- Adversarial attacks
- Model robustness
- Deep generative models
- PyTorch implementation
- GPU acceleration with CUDA
- Deep learning best practices

---

# 🛠️ Technologies

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Scikit-learn
- Pillow (PIL)

---

# 📂 Repository Structure

```text
generative-deep-learning-pytorch/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── notebooks/
│   ├── 01_autoencoder.ipynb
│   ├── 02_gan.ipynb
│   ├── 03_adversarial_attacks.ipynb
│   └── 04_generative_modeling.ipynb
│
├── Images/
│   ├── autoencoder_overview.png
│   ├── gan.png
│   └── adversarial_attack.png
│
└── models/
```

---


# 📖 Notebooks


## Notebook 1 — Autoencoders and Variational Autoencoders

<table>
<tr>
<td align="center" width="50%">

<img src="Images/Colorization.jpg" width="420">

**Colorization using Autoencoders**

</td>

<td align="center" width="50%">

<img src="http://kvfrans.com/content/images/2016/08/vae.jpg" width="420">

**Variational Autoencoder (VAE)**

</td>
</tr>
</table>

### Overview

This notebook introduces modern autoencoder architectures for unsupervised representation learning using PyTorch. It explores fully connected autoencoders, convolutional autoencoders, and variational autoencoders (VAEs), demonstrating how neural networks learn compact latent representations, reconstruct images, and generate new samples from learned probability distributions.

### Topics Covered

- Fully Connected Autoencoders
- Convolutional Autoencoders
- Variational Autoencoders (VAEs)
- Encoder–Decoder architectures
- Latent space representation learning
- Image reconstruction
- Image generation
- Transpose convolutions
- KL-divergence loss
- MNIST dataset
- Unsupervised learning

### Notebook

`notebooks/01_autoencoder.ipynb`


---

## Notebook 2 — Generative Adversarial Networks (GANs)

### Overview

This notebook demonstrates the implementation of Generative Adversarial Networks (GANs) using PyTorch. It explores adversarial training between generator and discriminator networks to synthesize realistic images from random latent vectors.

### Topics Covered

- Generative Adversarial Networks
- Generator architecture
- Discriminator architecture
- Adversarial training
- Latent space sampling
- Synthetic image generation
- Training stability
- Image synthesis

### Notebook

`notebooks/02_gan.ipynb`

---

## Notebook 3 — Adversarial Attacks

### Overview

This notebook explores adversarial attacks on deep neural networks by generating carefully crafted perturbations that cause image classifiers to produce incorrect predictions. It highlights the importance of robustness and security in deep learning models.

### Topics Covered

- Adversarial examples
- Fast Gradient Sign Method (FGSM)
- Model robustness
- Gradient-based attacks
- Perturbation analysis
- Classification robustness
- Neural network security

### Notebook

`notebooks/03_adversarial_attacks.ipynb`

---

## Notebook 4 — Generative Modeling

### Overview

This notebook explores advanced generative modeling techniques for learning data distributions and generating synthetic samples. It demonstrates how deep neural networks can model complex visual data through probabilistic and generative learning approaches.

### Topics Covered

- Deep generative models
- Image generation
- Latent variable models
- Representation learning
- Sampling techniques
- Synthetic data generation
- Deep learning workflows

### Notebook

`notebooks/04_generative_modeling.ipynb`

---

# 🎯 Learning Objectives

Throughout this repository, I explore how to:

- Build autoencoders for unsupervised representation learning.
- Learn compact latent representations of image data.
- Reconstruct images using encoder-decoder architectures.
- Generate realistic synthetic images using GANs.
- Evaluate neural network robustness using adversarial attacks.
- Understand modern generative deep learning techniques.
- Develop complete generative AI workflows using PyTorch.

---

# 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/Miladsaeedi70/generative-deep-learning-pytorch.git
```

Navigate to the project:

```bash
cd generative-deep-learning-pytorch
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebooks in numerical order:

1. Autoencoders
2. Generative Adversarial Networks
3. Adversarial Attacks
4. Generative Modeling

---

# ⭐ About

This repository showcases practical **Generative Deep Learning** projects developed with **PyTorch**. It demonstrates modern techniques for unsupervised representation learning, image generation, and neural network robustness through reproducible, well-documented implementations.

The notebooks have been reorganized and modernized to improve readability, reproducibility, and compatibility with current versions of PyTorch and Python.

---

# 📄 License

This repository is intended for educational and portfolio purposes.