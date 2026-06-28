# XplainQC-Glioma — Hybrid DL-VQC Glioma Classification (Results)

This repository showcases the **results** of a hybrid quantum-classical deep learning framework trained to classify brain glioma molecular subtypes into three categories: `Astrocytoma` , `Oligodendroglioma` , and `GBM (Glioblastoma)`.

> **Note:** Source code and implementation details are kept private. This repository contains only the model's performance results and training outputs.

## 📊 Results Summary

| Metric | Value |
|---|---|
| Final Test Accuracy (DNN-VQC) | 86.19% |
| Final Test Accuracy (Stacked Ensemble) | 87.62% |
| Macro Precision | 92.0% |
| Macro Recall (Sensitivity) | 92.0% |
| Macro F1-Score | 92.0% |
| AUC-ROC (DNN-VQC) | 0.906 |
| AUC-ROC (Stacked Ensemble) | 0.919 |
| 5-Fold CV Accuracy | 0.873 ± 0.022 |
| Best Validation Epoch | 40–60 / 100 |

*(Precision/Recall/F1 above are macro-averaged across all three glioma subtypes on the 210-patient held-out test set.)*

## 📈 Training History

![Training History](results/training_history.png)

## 🔢 Confusion Matrix

![Confusion Matrix](results/confusion_matrix.png)

## 📉 ROC Curves

![ROC Curves](results/roc_curves.png)

## 🗂️ Repository Structure

```
.
├── README.md
└── results/
    ├── training_history.png
    ├── confusion_matrix.png
    └── roc_curves.png
```

## ℹ️ About

This project explores hybrid quantum-classical architectures applied to brain tumor genomics. Implementation details, circuit architecture, and training code are not publicly shared.
