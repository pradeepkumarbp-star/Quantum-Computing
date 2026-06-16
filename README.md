# Chest X-Ray Classification — Hybrid Quantum-Classical CNN (Results)

This repository showcases the **results** of a hybrid quantum-classical deep
learning model trained to classify chest X-ray images into three categories:
`Lung_Opacity`, `Normal`, and `Viral Pneumonia`.

> **Note:** Source code and implementation details are kept private.
> This repository contains only the model's performance results and
> training outputs.

## 📊 Results Summary

| Metric                     | Value   |
|------------------------------|---------|
| Final Test Accuracy           | 92.22%  |
| Macro Precision                | 92.72%  |
| Macro Recall (Sensitivity)     | 92.68%  |
| Macro F1-Score                  | 92.69%  |
| Best Validation Epoch           | 21 / 25 |

*(Precision/Recall/F1 above are computed directly from the confusion matrix counts.)*

## 📈 Training History

![Training History](results/training_history.png)

## 🔢 Confusion Matrix

![Confusion Matrix](results/confusion_matrix.png)

## 📁 Repository Structure

```
.
├── README.md
└── results/
    ├── training_history.png
    ├── confusion_matrix.png
    └── metrics_report.txt
```

## ℹ️ About

This project explores hybrid quantum-classical architectures applied to
medical imaging. Implementation details, architecture, and training code
are not publicly shared.
