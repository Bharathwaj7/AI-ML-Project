# AI & ML Project Showcase

Welcome to the AI & ML Project Showcase, a curated collection of your advanced machine learning and general artificial intelligence projects. Each project includes a brief overview, key features, and instructions for setup and usage. Clone this repository and explore the cutting-edge models and techniques you’ve implemented.

---

## K-Means Clustering on Text

**Unsupervised learning technique for text data**

### Overview

Cluster sentences or documents into coherent groups using Sentence-Transformers embeddings and the K-Means algorithm.

### Features

- Embedding generation via `all-MiniLM-L6-v2`
- Configurable number of clusters
- Automatic assignment of new sentences to existing clusters
- Support for both fixed- and unknown-cluster scenarios (K-Means & Agglomerative)

### Usage

#### Install dependencies:

```bash
pip install sentence-transformers scikit-learn numpy
```
## Zero-Shot Classification
**Advanced ML classification without training examples**

## Overview
Leverage CLIP’s joint image-text embedding space to classify images into arbitrary classes (e.g., “cat” vs. “dog”) without fine-tuning.

### Features
- Image embedding via clip-ViT-B-32
- Text-label embedding in the same latent space
- Cosine similarity for label prediction
- Visual preview of sample predictions
### Usage

#### Install dependencies:

```bash
pip install sentence-transformers torch pillow matplotlib
```
## Unsupervised Image Clustering
**Machine learning approach for image grouping**

## Overview
Detect visually similar or duplicated images by clustering CLIP-derived image embeddings.

### Features
- Batch encoding of images via clip-ViT-B-32
- Cosine-similarity community detection
- Threshold-based clustering for near-duplicate detection
- Visualization of the top communities
### Usage

#### Install dependencies:

```bash
pip install sentence-transformers torch pillow matplotlib
```
## Contributing
Contributions, issues, and feature requests are welcome!
Feel free to fork the repository and submit a pull request.

## License
This project is licensed under the **MIT License**.
