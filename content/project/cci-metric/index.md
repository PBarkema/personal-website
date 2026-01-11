---
title: "Cross-Category Information (CCI)"
summary: "A novel statistical framework to quantify informative variance in cortical noise using manifold learning."
tags:
  - Statistics
  - Manifold Learning
  - Python
  - Information Theory
categories:
  - Methodology
  - Representations
date: "2024-06-01"

# External links to code or related papers
url_code: "https://github.com/PBarkema/Donders-IV-code-portfolio"

image:
  caption: "Decoding Neural Manifolds"
  focal_point: "Center"
---

### The Challenge: Signal vs. Noise
In neuroimaging, "noise" is often defined as trial-to-trial variability that doesn't match the stimulus. However, much of this variability is shared across neuronal populations and may represent top-down feedback or internal predictions. 

### The Innovation: The CCI Metric
I invented the **Cross-Condition Information (CCI)** metric to quantify how much of this "noise" is actually structured and informative. With **Manifold Learning** (PCA) and **Subspace Alignment**, CCI measures the overlap between variation in neural representation spaces across objects from the same category (i.e. different animals).

### Technical Implementation
* **Manifold Alignment:** Developed algorithms to align low-dimensional latent representations.
* **Noise Decoding:** Demonstrated that trial-by-trial variability is not stochastic but follows a specific geometric structure that predicts behavioral outcomes.
* **High-Performance Computing:** Optimized the pipeline in **Python (NumPy/SciPy)** to process multi-terabyte datasets across HPC clusters.

### Scientific Impact
CCI provides a tool for researchers to interrogate how informative **noise** in the brain is for **object classification** in human vision.