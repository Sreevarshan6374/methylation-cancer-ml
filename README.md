# methylation-cancer-ml
# 🧬 DNA Methylation-Based Cancer Classification

This project applies **machine learning** to synthetic DNA methylation data to classify between **cancerous** and **normal** samples using Random Forest. It mimics real-world bioinformatics workflows for epigenetic cancer biomarker discovery.

---


---

## 📊 Dataset

- **Type**: Synthetic CpG site methylation matrix
- **Samples**: 100
- **Features**: 50 simulated CpG sites
- **Labels**: `0` (normal) or `1` (cancer)

Each feature represents the **methylation level** (β-value) of a CpG site (range 0–1).

---

## 🤖 Model

- **Algorithm**: Random Forest Classifier (`sklearn`)
- **Evaluation**: Accuracy, Precision, Recall, F1-score
- **Result** (on synthetic data):  
Accuracy: 0.50
F1-score: 0.50


