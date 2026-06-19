# AI-Driven Virtual Screening for Drug Discovery

## 🧬 Project Overview
Bringing a new drug to market takes over a decade. 
As a biotechnology student, I want to bridge the gap between wet-lab biological research and computational data science. This repository serves as my hands-on exploration into how Machine Learning can optimize early-stage drug discovery, significantly cutting down the time and high costs traditionally required to find viable drug candidates.

## 📊 Dataset & Target Focus
* **Target Organism / Disease:** I am focusing this pipeline on screening compounds against specific cancer-related target proteins (e.g., Human EGFR).
* **Data Sourcing:** Raw bioactivity data, IC50 values, and chemical structures are fetched programmatically from the public [ChEMBL Database](https://ebi.ac.uk).
* **Languages:** Python (Jupyter Notebooks)
* **Core Libraries:** 
  * `RDKit` (Chemical structure manipulation & feature extraction)
  * `Scikit-Learn` (Machine learning classifiers)
  * `Pandas` & `NumPy` (Data processing)

## 🛠️ Pipeline Workflow
1. **Data Ingestion:** Fetching bioactivity data for a specific target protein.
2. **Data Cleaning:** Filtering missing IC50 values and handling duplicate chemical structures.
3. **Feature Engineering:** Converting chemical **SMILES strings** into numerical **Morgan Fingerprints** using RDKit.
4. **Model Training:** Evaluating Random Forest and XGBoost classifiers to separate active compounds from inactive ones.

## 📁 Repository Structure
* `notebooks/`: Contains step-by-step Jupyter Notebooks for data cleaning and model training.
* `src/`: Production-ready Python scripts exported for scalable screening pipelines.

---
Maintained by GARGEE CHOUDHARY (B.Tech Biotechnology student)
