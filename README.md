# Brain Tumor MRI Classification

This project uses deep learning to classify brain MRI images into tumor categories. It compares a baseline CNN model with a ResNet50 transfer learning model.

## Project Contents

- Brain MRI image preprocessing
- Exploratory visualization with PCA and t-SNE
- Baseline CNN model
- ResNet50 transfer learning model
- Model evaluation using accuracy, confusion matrix, ROC curves, and F1-score
- Grad-CAM visualization for model interpretability

## Dataset

The dataset should be organized as:

```text
archive/
├── Training/
└── Testing/
```

Update the dataset path in the notebook before running:

```python
data_dir = "path/to/archive"
```

## File

- `QBIO465_final_project_code.ipynb`

## Requirements

```text
tensorflow
numpy
pandas
matplotlib
seaborn
scikit-learn
```

## How to Run

1. Open `QBIO465_final_project_code.ipynb`.
2. Update the dataset path.
3. Run the notebook from top to bottom.

## Authors

Yutian He, Caroline Jiang, and YiAn Xu
