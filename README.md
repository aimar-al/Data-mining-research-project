# Algorithmic Family vs. Preprocessing Pipeline: Evaluating Non-Transferability and Model Dependency in Imbalanced Datasets

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.XXXXXXX.svg)](https://doi.org/10.5281/zenodo.XXXXXXX)  
*(This badge will become active after you publish the release on Zenodo. Replace XXXXXXX with your actual DOI.)*

## 📖 Project Description

This repository contains the final research project for the **Data Mining and Data Warehouse** course at **UNITBV**.

The main objective is not to find the "perfect" model, but rather to measure the impact of **preprocessing pipeline non‑transferability** across different families of machine learning algorithms.

Two classifier families are compared:

- **Distance family:** K‑Nearest Neighbors (KNN) and Logistic Regression.
- **Partition family (trees):** Decision Tree and Random Forest.

The study demonstrates that there is no universal pipeline: what optimizes one family can severely harm the other.

## 👥 Authors

- **Aimar Alustiza**
- **Fermín Barrena**

## 📄 Associated Paper

The full paper is available in this repository:  
👉 [`Paper.pdf`](./Paper.pdf)

## ⚙️ Repository Structure
├── Paper.pdf # Main paper  
├── research_code.ipynb # Notebook with all code and experiments  
├── data/  
│ └── bank-full.csv # Bank Marketing dataset (UCI)  
├── LICENSE # MIT license for the code  
├── LICENSE-CC-BY-NC-SA.md # CC BY-NC-SA 4.0 license for the paper and documentation  
└── README.md # This file
  
## 🔍 How to Run the Code

1. Clone this repository.
2. Open `research_code.ipynb` in Jupyter Notebook or Google Colab.
3. Run the cells in order. The notebook is self‑contained and uses the included dataset.

## 🔗 Citation and DOI

This project has been registered on Zenodo with a permanent DOI. If you use this work, please cite it as:

> Barrena, F., & Alustiza, A. (2026). *Algorithmic Family vs. Preprocessing Pipeline: Evaluating Non‑Transferability and Model Dependency in Imbalanced Datasets*. Zenodo. https://doi.org/10.5281/zenodo.XXXXXXX

(The DOI will be updated after the first release on Zenodo.)

## 📜 Licenses

This repository contains **software** and **academic content** under different licenses, depending on the file type:

### 1. Source code (`research_code.ipynb`)

Distributed under the **MIT license**. See the full text in the [`LICENSE`](./LICENSE) file.

This means you can use, copy, modify, and distribute the code freely, even for commercial purposes, as long as you include the original copyright notice.

### 2. Academic paper (`Paper.pdf`), documentation and images

Distributed under the **Creative Commons Attribution‑NonCommercial‑ShareAlike 4.0 International (CC BY‑NC‑SA 4.0)** license.  
The full legal text is available in [`LICENSE-CC-BY-NC-SA.md`](./LICENSE-CC-BY-NC-SA.md).

Under this license, you may share and adapt the content, provided that:
- You give appropriate credit to the authors.
- You do not use it for commercial purposes.
- If you make changes, you distribute them under the same license.

### 3. Dataset (`bank-full.csv`)

This dataset comes from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/222/bank+marketing) and is licensed under **Creative Commons Attribution 4.0 International (CC BY 4.0)**.

Therefore, the following attribution is required:

> Moro, S., Cortez, P., & Rita, P. (2014). A data‑driven approach to predict the success of bank telemarketing. *Decision Support Systems*, 62, 22‑31.

## 🙏 Acknowledgements

We thank the dataset creators for making it publicly available, and the teaching staff of the Data Mining and Data Warehouse course for their guidance during the development of this project.

---

*Last updated: June 2026*