# CNV-Detection-HMM_BioInformatics
Colab notebook for CNV (Copy Number Variation) detection using Hidden Markov Models (HMM). Identifies deletions, duplications, and normal states by modeling genomic data and inferring the most likely copy number state sequence using the Viterbi algorithm.
#  CNV Detection Using Hidden Markov Models (HMM) – Google Colab Project

This project demonstrates a simple and effective approach to detecting **Copy Number Variations (CNVs)** in genomic data using **Hidden Markov Models (HMMs)**, implemented in Python via Google Colab.

---

##  Overview

Copy Number Variations are structural changes in the genome where certain regions are **deleted** (loss) or **duplicated** (gain), altering the number of DNA copies in that region. These variations are important in understanding diseases like **cancer**, **genetic syndromes**, and **rare disorders**.

In this notebook, we simulate synthetic genomic read-depth data and use a Gaussian HMM to predict underlying copy number states. The model identifies:
-  **Deletions** – Low read depth
-  **Normal regions** – Baseline read depth
-  **Duplications** – High read depth

---

##  What This Project Does

1. **Generates synthetic read-depth data** to simulate normal, deletion, and duplication regions.
2. **Uses `hmmlearn`** to build and train a **Gaussian Hidden Markov Model** on the data.
3. **Infers hidden states** using the **Viterbi algorithm**.
4. **Visualizes** read-depth and predicted states alongside the ground truth.

---

##  Visual Output

The notebook includes visualizations showing:
- Raw read-depth data across genomic positions
- Highlighted CNV regions (true deletions/duplications)
- Detected hidden states, helping you compare model output vs ground truth

---

##  Requirements

Listed in `requirements.txt`:

