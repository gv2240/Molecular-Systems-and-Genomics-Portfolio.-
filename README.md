# Molecular Discovery & Bioinformatics Reference Library

### **Molecular Systems Researcher | Python Developer**
> Specialized in modernizing high-throughput discovery pipelines and transitioning legacy HTS/genomic workflows into scalable Python ecosystems.

---

## 🔬 Project Overview
This repository contains a modular collection of bioinformatics workflows transitioned from legacy instructional formats (R/Excel) into production-grade Python. It demonstrates the ability to handle biological data from the initial signal identification through to predictive modeling and statistical validation.



---

## 📁 Repository Structure

### **01. Differential Expression**
*Focus: Extracting biological signals from high-throughput noise.*
* **`HTS_Normalization_&_QC.ipynb`**: Modernizes HTS plate processing. Includes automated 4-Parameter Logistic (4PL) curve fitting and Z'-factor calculation.
* **`RNAseq_Count_Normalization.ipynb`**: Handles the merging of genomic replicates and distribution visualization using violin plots.

### **02. Sequence Evolution**
*Focus: Understanding molecular history and conservation via Biopython.*
* **`Biopython_Sequence_Parsing.ipynb`**: Foundational handling of FASTA/GenBank formats.
* **`Sequence_Alignment_Significance.ipynb`**: Calculating p-values to distinguish biological signal from random noise in sequence alignments.
* **`Phylogenetic_Tree_Construction.ipynb`**: Building and visualizing evolutionary relationships using Distance-Matrix methods.

### **03. Predictive Modeling**
*Focus: Applying Machine Learning to classify biological states.*
* **`Logit_Regression_Diagnostics.ipynb`**: Logistic regression for binary classification of molecular features.
* **`Random_Forest_Molecular_Prediction.ipynb`**: High-performance classification using Ensemble Learning to identify malignant vs. benign samples, featuring ROC/AUC analysis.

### **04. Statistical Foundations**
*Focus: The mathematical rigor ensuring discovery accuracy.*
* **`Hypothesis_Testing_&_Sampling.ipynb`**: Demonstrates population sampling, T-tests, and the importance of statistical power in molecular research.

---

## 🛠 Tech Stack
* **Languages:** Python (Primary), R (Legacy Reference)
* **Libraries:** `Pandas`, `NumPy`, `SciPy`, `Biopython`, `Scikit-Learn`
* **Visuals:** `Matplotlib`, `Seaborn`

---

## 📈 The Modernization Advantage
By moving from manual or R-based legacy scripts to vectorized Python, these workflows achieve higher throughput and better reproducibility.

| Feature | Legacy Workflow (R/Excel) | Modernized Pipeline (Python) |
| :--- | :--- | :--- |
| **Data Handling** | Manual/Row-by-Row | Vectorized (Pandas/NumPy) |
| **Scalability** | Limited by local RAM | Memory-mapped / Parallelized |
| **Validation** | Visual Inspection | Automated QC (e.g., Z'-factor) |

### **Quality Control Logic**
We utilize the Z'-factor to ensure every high-throughput plate is statistically robust before downstream analysis:

$$Z' = 1 - \frac{3(\sigma_p + \sigma_n)}{|\mu_p - \mu_n|}$$

---

## 📧 Contact
I am interested in roles involving **HTS automation**, **genomic pipeline modernization**, and **computational biology**. Reach out via GitHub or LinkedIn!
