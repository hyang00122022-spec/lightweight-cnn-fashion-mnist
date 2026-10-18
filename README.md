# Lightweight CNN for Fashion-MNIST Classification

**Lightweight CNN with Data Augmentation and Batch Normalization for Fashion-MNIST Classification**

[![Preprint](https://img.shields.io/badge/Preprint-Preprints.org-blue)](https://doi.org/10.20944/preprints202605.1915.v1)
[![Dataset](https://img.shields.io/badge/Dataset-Fashion--MNIST-orange)](https://github.com/zalandoresearch/fashion-mnist)
[![Framework](https://img.shields.io/badge/Framework-TensorFlow%20%2F%20Keras-orange)](https://www.tensorflow.org/)

## 📄 Research Paper

**Title:** Lightweight CNN with Data Augmentation and Batch Normalization for Fashion-MNIST Classification

**Authors:** Tao Jingchu, Abdul Salam Shah, Aisha Farooq

**Posted Date:** 28 May 2026

**DOI:** [10.20944/preprints202605.1915.v1](https://doi.org/10.20944/preprints202605.1915.v1)

**Publication Status:** Preprint — not peer-reviewed in this version.

Read the full paper: [View the research paper](https://doi.org/10.20944/preprints202605.1915.v1)

## 🔍 Project Overview

This project investigates lightweight Convolutional Neural Networks (CNNs) for image classification using the Fashion-MNIST dataset. The research focuses on improving classification performance while maintaining a relatively simple and computationally efficient model architecture.

The study explores techniques including data augmentation, batch normalization, dropout, and early stopping to support model training, improve generalization, and reduce overfitting.

The project aims to contribute to the understanding of how lightweight CNN architectures and training strategies can be applied to image classification tasks.

## 🎯 Research Objectives

- Develop and evaluate lightweight CNN architectures for Fashion-MNIST classification.
- Investigate the role of data augmentation in model generalization.
- Examine batch normalization as a training and optimization technique.
- Explore dropout and early stopping as regularization strategies.
- Analyze classification performance and the trade-offs associated with lightweight model design.
- Support reproducible research through organized experimental code and results.

## 🧪 Dataset

**Fashion-MNIST** is a benchmark dataset consisting of grayscale images of fashion products across 10 categories.

- Training images: 60,000
- Test images: 10,000
- Image dimensions: 28 × 28 pixels
- Number of classes: 10
- Image format: Grayscale

Dataset source: [Fashion-MNIST — GitHub](https://github.com/zalandoresearch/fashion-mnist)

## 🧠 Methodology

The research focuses on the following components:

| Component | Purpose |
|---|---|
| Lightweight CNN | Extract image features with a relatively compact architecture |
| Data augmentation | Introduce training-image variations to support generalization |
| Batch normalization | Normalize intermediate activations during training |
| Dropout | Help reduce overfitting |
| Early stopping | Stop training when the monitored validation metric no longer improves |
| Model evaluation | Assess classification performance on the test dataset |

The actual model configurations and experimental settings should be documented alongside the corresponding notebooks or source files.

## 🛠️ Technologies

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- scikit-learn
- Google Colab / Jupyter Notebook

## 📂 Repository Structure

```text
lightweight-cnn-fashion-mnist/
│
├── README.md
├── notebooks/
│   └── fashion_mnist_experiments.ipynb
├── models/
├── results/
├── figures/
└── paper/
    └── research_paper.pdf
```

*Note: This is a suggested structure. Update it to match the files actually available in the repository.*

## 📊 Experimental Results

Experimental results should be reported using verified measurements from the completed runs.

Recommended evaluation metrics include:

- Test accuracy
- Precision, recall, and F1-score
- Confusion matrix
- Number of trainable parameters
- Training time and inference time, where measured

Results from different model configurations should be compared under consistent evaluation conditions. No performance values are reported here until the corresponding experimental results have been verified.

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
cd YOUR_REPOSITORY
```

Replace `YOUR_USERNAME` and `YOUR_REPOSITORY` with the actual GitHub username and repository name.

### 2. Install dependencies

```bash
pip install tensorflow numpy matplotlib scikit-learn
```

### 3. Run the experiments

Open the relevant Jupyter Notebook in Google Colab or run it locally in a compatible Python environment.

Follow the notebook instructions to load Fashion-MNIST, configure the model, train the network, and evaluate its performance.

## 🔁 Reproducibility

For reproducible experiments, document the following information where applicable:

- Dataset source and preprocessing steps
- Model architecture and hyperparameters
- Data augmentation settings
- Training and validation configuration
- Random seeds
- Software and library versions
- Evaluation procedures
- Saved model checkpoints and experimental results

## 📚 Citation

If you use or discuss this research, please cite the preprint:

Tao Jingchu, Abdul Salam Shah, and Aisha Farooq. *Lightweight CNN with Data Augmentation and Batch Normalization for Fashion-MNIST Classification*. Preprints.org, posted 28 May 2026.

DOI: https://doi.org/10.20944/preprints202605.1915.v1

## 📜 License

The paper is distributed under the license specified on its Preprints.org record. The license for this repository's source code and other materials should be specified separately.

## 👩‍💻 Authors

- **Tao Jingchu**
- **Abdul Salam Shah**
- **Aisha Farooq**

---

*This repository is intended to support transparent documentation and reproducible experimentation in lightweight deep learning for image classification.*
