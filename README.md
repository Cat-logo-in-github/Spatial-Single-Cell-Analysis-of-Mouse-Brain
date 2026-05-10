# Spatial Mouse Brain Explorer

[![#Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Cat-logo-in-github/Spatial-Single-Cell-Analysis-of-Mouse-Brain/blob/main/Spatial_Single_Cell_Analysis.ipynb)

An interactive beginner-friendly notebook for exploring spatial transcriptomics data from the mouse brain using Scanpy and Squidpy.

---

## Features

- Visualize spatial gene expression
- Explore cell clusters using Leiden clustering
- Compare UMAP gene-similarity maps with physical spatial maps
- Generate colorful spatial heatmaps
- Modify simple parameters to explore different genes and regions

---

## Learning Goals

Students will learn how to:

1. Understand the difference between whole-organ analysis and single-cell analysis
2. Identify different cell populations using gene expression
3. Visualize spatial organization of cells in the mouse brain
4. Explore basic clustering and pattern discovery techniques

---

## Dataset

Built using publicly available mouse brain datasets from 10x Genomics

---

## Intended Audience

Designed for:
- high school students
- introductory bioinformatics courses
- spatial biology workshops
- beginners in single-cell analysis

No prior biology or programming experience is required.

---

## Quick Start

Open the notebook in Google Colab using the badge above and run the cells in order.

Students can explore different genes simply by changing:

```python
GENE = "Reln"
```

to another gene such as:

```python
GENE = "Gad1"
```

---

## Technologies Used

- Python
- Scanpy
- Squidpy
- NumPy
- Matplotlib
- Seaborn

---
