# Computational Biotechnology & AI Portfolio

Welcome to my dry-lab research repository. As a biotechnology student, I bridge the gap between molecular biology and computer science. This portfolio contains end-to-end computational pipelines tracking chemical informatics, predictive machine learning, and structural viral genomics.

---

## 🔬 Project 1: AI-Driven Virtual Screening for Drug Discovery
**Directory:** `notebooks/01_virtual_screening_egfr.ipynb`

### 🧬 Project Overview
Bringing a new drug to market takes over a decade. This project demonstrates how Machine Learning can optimize early-stage drug discovery, significantly cutting down the time and high costs traditionally required to find viable drug candidates against cancer-related proteins.

### 📊 Methodology & Results
* **Data Sourcing:** Raw bioactivity data and IC50 concentration values were mined programmatically from the public **ChEMBL Database**.
* **Feature Engineering:** Converted chemical SMILES strings into 2048-bit structural mathematical arrays (**Morgan Fingerprints**) using **RDKit**.
* **AI Architecture:** Trained a Scikit-Learn **Random Forest Classifier** to distinguish active cancer inhibitors from inactive molecules.
* **Evaluation Score:** The model achieved an **84.21% Accuracy Score** on unseen clinical test compounds.

---

## 🧬 Project 2: SARS-CoV-2 Computational Genomic Analyzer
**Directory:** `notebooks/02_genomic_sequence_analysis.ipynb`

### 🦠 Project Overview
Viral mutations constantly alter structural protein stabilities. This pipeline automates the retrieval, quality mapping, and nitrogenous base analysis of viral genomes directly from federal repositories to evaluate molecular heat thresholds.

### 📊 Methodology & Results
* **Data Sourcing:** Automated a live server handshake to pull the complete reference genome of the original SARS-CoV-2 strain from the **NCBI GenBank** database using **Biopython**.
* **Sequence Metrics:** Parsed a raw text FASTA sequence measuring **29,903 biological letters long**.
* **Analytics Matrix:** Calculated the exact frequency distribution of Adenine, Thymine, Guanine, and Cytosine using **Pandas**.
* **Biotech Insight:** Discovered an **Overall GC-Content of 37.97%**. Because AT bonds share fewer hydrogen links than GC bonds, this low percentage computationally explains the virus's structural fragility under heat and soap.

---

## 🛠️ Tech Stack Summary
* **Languages:** Python (Jupyter Notebooks)
* **Domain Libraries:** RDKit, Biopython
* **Data & Core ML:** Pandas, NumPy, Scikit-Learn, Matplotlib

---
*Maintained by Gargee Choudhary (B.Tech Biotechnology student)*
