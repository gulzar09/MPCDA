# MPCDA: Multi-Prototype Cross-Lingual Domain Adaptation for Bangla Text Emotion Recognition

This repository contains the implementation of **MPCDA**, a cross-lingual emotion recognition framework designed to improve Bangla emotion classification by transferring knowledge from high-resource source languages.

MPCDA combines multilingual representation learning, emotion-aware alignment, prototype-based transfer learning, and domain adaptation strategies to learn robust and language-invariant emotional representations.

## Overview

The framework consists of the following components:

* Shared Multilingual Encoder
* Self-Attention Emotion Classifier
* Emotion-Aware Cross-Lingual Alignment
* Prototype-Based Emotion Transfer
* Language Adversarial Adaptation

The model is designed for:

* Zero-shot emotion transfer
* Full-shot learning
* Low-resource Bangla emotion recognition

## Repository Structure

```text
MPCDA.ipynb        # Complete implementation and experiments
README.md          # Project description
```

## Requirements

* Python 3.10+
* PyTorch
* Transformers
* NumPy
* Pandas
* Scikit-learn
* Matplotlib

## Usage

Open and execute the notebook sequentially:

```bash
jupyter notebook MPCDA.ipynb
```

## Research Status

This work is currently under review for journal submission.

To maintain research integrity, only partial implementation code is currently provided. Detailed methodological descriptions, trained models, datasets, and experimental resources will be released after publication.

## Citation

Citation information will be added upon publication.

## License

This repository is intended for academic and research purposes.

